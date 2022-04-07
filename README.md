# elasticsearch_7.17.2_crack
elasticsearch 7.17.2 crack file
![image](https://user-images.githubusercontent.com/20622517/162134930-bcb3fe25-0cf9-4db1-9532-691d87eeb1f3.png)
![1649313229(1)](https://user-images.githubusercontent.com/20622517/162135041-c75a242e-c0a3-40ac-ab63-4a7d6db9a818.png)

# usage
Replace the original JAR file directly with the jar file of the repository

origin jar file location: /usr/share/elasticsearch/modules/x-pack-core/x-pack-core-7.17.2.jar

# backup code

```
# build XpackBuild.java
javac -cp "C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\modules\x-pack-core\x-pack-core-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\lucene-core-8.11.1.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-core-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-x-content-7.17.2.jar"  XPackBuild.java


# build LicenseVerifier.java
javac -cp "C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\modules\x-pack-core\x-pack-core-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\lucene-core-8.11.1.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-core-7.17.2.jar;C:\Users\Administrator\Desktop\elasticsearch-7.17.2\elasticsearch-7.17.2\lib\elasticsearch-x-content-7.17.2.jar"  LicenseVerifier.java

# replace x-pack-core-7.17.2.jar in docker
docker cp /home/es/x-pack-core-7.17.2.jar c776828b19e3:/usr/share/elasticsearch/modules/x-pack-core/x-pack-core-7.17.2.jar
```
