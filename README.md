# TizenPlatformBuild
Tizen Platform Build Test

* 빌드 진행 과정 참고 문서
  * https://docs.google.com/document/d/15hBbNG2BW1A9ZROwhAe_8Yn4buzbb_O7TTfhv5k2usI/edit?usp=sharing

* 빋드 결과
  * 80GB 상당의 소스를 받고 빌드를 하였지만, 성공하지 못함
  
tizen@tizen-dev:~/Tizen_Project$ df -h
Filesystem      Size  Used Avail Use% Mounted on
udev            1.9G     0  1.9G   0% /dev
tmpfs           395M  6.1M  389M   2% /run
/dev/sda1       244G  107G  126G  46% /
tmpfs           2.0G  132K  2.0G   1% /dev/shm
tmpfs           5.0M  4.0K  5.0M   1% /run/lock
tmpfs           2.0G     0  2.0G   0% /sys/fs/cgroup
tmpfs           395M   72K  395M   1% /run/user/1000
tizen@tizen-dev:~/Tizen_Project$ 

* 결론
  * IoT-headed 플랫폼을 Tizen Wearable 플랫폼 이미지 수준으로 업그래드 하기 위해서 많은 패키지들의 조합이 필요함
