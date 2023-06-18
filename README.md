# Flask-HelloWorld-Docker
image build-
docker build -t sakibtamim/flash-helloworld-docker:0.0.1.RELEASE .
run container-
docker container run -d -p 5000:5000 sakibtamim/flash-helloworld-docker:0.0.1.RELEASE
stop container-
docker container stop (image codde)
docker push to hub-
docker push sakibtamim/flash-helloworld-docker:0.0.1.RELEASE
