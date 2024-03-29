### BitBSD jail repo ###

`$ curl https://bitclouds.sh/images`

````
{
  "images": [
    "bitcoind", 
    "lightningd", 
    "rootshell"
    "debian", #non-jail 
    "centos", #non-jail
    "ubuntu" #non-jail
  ]
}
````



`$ curl https://bitclouds.sh/create/rootshell`

````
{
  "host": "BarnardsStar", 
  "paytostart": "lnbc3627320p1pwm630spp5twdd9yq5mufat0fagrxr8fjfkhahfcuxuda5lfs9alafvyp0vpwqdq5gfshymnpwfj8x5m5v9eqxqzjccqp2rzjq0hpsr5wupl3l8yeslvckh2aanmt447stz7a3036m97gurwjehrm5zxy4cqq0scqqqqqqqpgqqqqqzqqzsh8z7nj3vqknrumrtv84erxdzpfg5tr5knys5c3r7d2mfpc9dzm6psz4sstzrc36040pntdv9s484au4xdhvc9mvx9a8zcrexnr9h6zqp7gm7kk"
}
````


`$ curl https://bitclouds.sh/status/BarnardsStar`

````
{
  "status": "awaiting payment! if you paid already wait until your instance is created."
}
````



`$ curl https://bitclouds.sh/status/BarnardsStar`

````
{
  "app_port": 52434,
  "hours_left": 4,   
  "ip": "bitbsd.org", 
  "ssh_port": 62933,
  "ssh_pwd": "e8c4ebd9b8d0e0aa",
  "ssh_usr": "satoshi",
  "status": "subscribed"
}
````

`$ curl https://bitclouds.sh/topup/Taiyangshou/150`
````
{
  "invoice": "lnbc1500n1pwm6j23pp5yfjxkup92ru8xgnany9g0tlmc39a27354vpcd4lcghlzns20yczqdqj23skj7tpdenhx6r0w5xqzjccqp2rzjqfxj8p6qjf5l8du7yuytkwdcjhylfd4gxgs48t65awjg04ye80mq7zx8dgqqy9gqqyqqqqqqqqqqvsqqrctl0e2gdcjnz5lv52v9gss7aww5wrle9c78qnwtvy4nywp30kydlreaywwjxawr8vnluak836wnlvvc3j0xvpvglqg2xrsx2y3ep3m8qp35p59r"
}
````

**Jail features**

Built-in TOR - there is no other way to access internet

Transparent full data encryption

Redundand storage array with data integrity checks

Security-hardened enviroment

OS level process isolation

Highly restricted application user permissions