# homestead

安装好virtualbox和vagrant后

使用homestead 

```
homestead/bin/homestead make

cp Homestead.yaml Homestead.mac.yaml

cp Homestead.yaml Homestead.windows.yaml
```

## windows系统
```
cd platform\windows

vagrant up

vagrant ssh


```


## mac系统
```
cd platform/mac

vagrant up

vagrant ssh

```

## 更改了homestead的配置，需要重启
```
vagrant reload --provision
```
