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
Eğer bu ekranda CTRL + C yaparsanız nodeyi durdurursunuz çalıştırma kodunu tekrar girmeniz gerekir.
Nodeyi durdurmadan çıkmak için CTRL + A + D tuşlarıyla screenden çıkıyoruz.

Tohum kelimelerini ve pubkey'i almak için kodları yazıyoruz.

Tohum kelimelerini görme kodu ;

```
sudo cat $HOME/nubit-node/mnemonic.txt
```

Pubkey görme kodu ;
```
$HOME/nubit-node/bin/nkey list --p2p.network nubit-alphatestnet-1 --node.type light
```
![image](https://github.com/DoganSoley/nubit/assets/110679236/57d1263e-e2ff-4a07-83d1-2180cdf60686)
Okla işaretlediğim yer " " arasında olan adres sizin pubkeyiniz.
