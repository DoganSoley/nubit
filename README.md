![image](https://github.com/DoganSoley/nubit/assets/110679236/082cde6b-ee7e-4aee-9a43-897d152c1ac2)

# Nubit Light Node Gereksinimleri

Minimumda bir sistem yeterli olur ben;

2GB Ram

2GB CPU

40GB SSD

Sisteme kurulum yaptım.


Sunucuya bağlandıktan sonra sırayla ;

```
sudo apt-get update && sudo apt-get upgrade -y
```
Yükleme bittikten sonra ;

```
sudo apt-get install curl screen git-all build-essential glibc-source pkg-config libssl-dev clang git-lfs -y
```

Yükleme bittikten sonra screen açalım ;

```
screen -S nubit
```

Daha sonra node çalıştırma kodu ;
```
curl -sL1 https://nubit.sh | bash
```
