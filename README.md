# speedtest

gitlab.com is slower than github.com

## try yourself

    bash <(curl -s https://gitlab.com/wridgers/speedtest/raw/master/speedtest)

(you probably should't do this... at least read the script first...)

## example output

    clone git@github.com:wridgers/speedtest.git -> ./github_ssh: 0:01.18
    clone git@gitlab.com:wridgers/speedtest.git -> ./gitlab_ssh: 0:01.56
    clone https://github.com/wridgers/speedtest.git -> ./github_https: 0:00.60
    clone https://gitlab.com/wridgers/speedtest.git -> ./gitlab_https: 0:00.89
    pull ./github_ssh: 0:01.09
    pull ./gitlab_ssh: 0:01.55
    pull ./github_https: 0:00.50
    pull ./gitlab_https: 0:00.56
