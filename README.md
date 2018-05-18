## What is this

[google/dagger/examples](https://github.com/google/dagger/tree/master/examples) を java (not android) + gradle + eclipse で 実行する

## Constitution

- java : 1.8
- gradle : 3.5
- eclipse : 4.7.2
- dagger : 2.16
- net.ltgt.apt : 0.15

## Usage

1. ./gradlew eclipse
1. ./gradlew build
1. CoffeeApp を 実行
1. 実行結果
```
~ ~ ~ heating ~ ~ ~
=> => pumping => =>
 [_]P coffee! [_]P 
```

変更した場合は、  
プロジェクト右クリック.Gradle.Refresh Gradle Project で  
.apt_generated が更新される