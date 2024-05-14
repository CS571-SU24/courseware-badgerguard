```
docker build . -t ctnelson1997/cs571-su24-badgerguard
docker push ctnelson1997/cs571-su24-badgerguard
```

```
docker pull ctnelson1997/cs571-su24-badgerguard
docker run -dit --restart=always --name cs571_su24_badgerguard -p 31667:80 ctnelson1997/cs571-su24-badgerguard
```
