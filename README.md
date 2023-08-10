



## Sistem Gereksinimleri
| Bileşenler | Minimum Gereksinimler | 
| ------------ | ------------ |
| CPU |	4|
| RAM	| 8+ GB |
| Storage	| 500 GB SSD |

## Update edelim
```bash
sudo apt update; sudo apt upgrade 
```
## Docker kurulumu
```bash
sudo apt-get install wget && sudo apt-get update && sudo apt install jq git && sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin 

```
## Erbie Kurulum
```
wget -O erbie_install.sh https://docker.erbie.io/erbie_install.sh && sudo bash erbie_install.sh
```

👉 Private keyimizi girelim.

![image](https://github.com/molla202/Erbie/assets/91562185/98bf6fcc-67c6-4470-84ba-b4ac3298d470)

👉Kurulum bittikten sonra çıktımız.

![image](https://github.com/molla202/Erbie/assets/91562185/28e40ee6-0bfa-485c-a7f2-71aebdfa27bf)

👉 docker ps -a diyoruz ve status kısmında çalıştığını teyit ediyoruz. unutmayın 8545 portunu kullanıyoruz bu yuzden baska bişi kullanmadığındna emin olunuz.

![image](https://github.com/molla202/Erbie/assets/91562185/7f47a89c-f9c6-4139-843a-e7686606688b)
