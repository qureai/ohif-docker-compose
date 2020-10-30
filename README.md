# OHIF docker compose

Docker compose for OHIF dicom viewer. You can deploy a PACS and fully featured dicom viewer in a single line.

## Run OHIF and Orthanc

```
git clone https://github.com/chsasank/ohif-docker-compose
cd ohif-docker-compose
docker-compose up -d
```

Open http://localhost:3000 in your browser and you should see this:

![Ohif viewer](./ohif.png)

## Stop the service

```
docker-compose down
```