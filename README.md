    FROM openjdk

    WORKDIR /app

    COPY ./First.java .

    RUN javac First.java

    CMD ["java","First"]

docker build -t firshe .
docker run firshe
docker images
docker rm 7ca
docker rmi imageid

FOR GIT

git clone 
cd 
git config --global user.name "PragalbahSalunke"
git config --global user.email "salunkepragalbha99@gmail.com"
git add .
git commit -m "khgyuf"
git push origin main
git pull

