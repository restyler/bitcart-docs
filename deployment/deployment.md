# Choosing a Deployment Method

There are several different deployment methods available, all using the same BitcartCC software. Because BitcartCC is a free and open-source all-in-one crypto solution, we support diversity in deployment methods for users. Different solutions work best for [different use cases](../bitcartcc-basics/use-case.md).

Business deployment methods can vary by setup, maintenance, support, price, etc. You can run BitcartCC as a self-hosted solution on your own server, or use a third-party host. The self-hosted solution allows you not only to attach an unlimited number of stores but also become a payment processor for others.

BitcartCC is a non-custodial invoicing system which eliminates the involvement of a third-party when managing funds. Payments with BitcartCC go directly to your wallet. Your private keys are never uploaded to the server. Meaning 3rd Party BitcartCC hosts do not control user funds, they are simply hosting your instance of the BitcartCC software for you.

Developer deployments are not recommended for production environments and require the user to have technical knowledge related to the build.

![Pick your deployment method](../.gitbook/assets/bitcartcc\_deployment.png)

## What are my options?

* ​[LunaNode Web Deployment​](lunanodeweb.md)
* ​Azure Deployment​
* [​Docker Deployment​](docker.md)
* ​Google Cloud Deployment​
* [​Hardware Deployment​](hardware.md)
* [​Third-Party Hosting​](thirdpartyhosting.md)
* [​Manual Deployment](manual.md)

## To chose one that will best suit your needs, consider the following: <a href="#to-chose-one-that-will-best-suit-your-needs-consider-the-following" id="to-chose-one-that-will-best-suit-your-needs-consider-the-following"></a>

| Web Solutions                   |                                    1.                                    |                               2.                              |                                      Why?                                     |
| ------------------------------- | :----------------------------------------------------------------------: | :-----------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <p>Business<br>(Fast Setup)</p> | <p><a href="thirdpartyhosting.md">3rd Party <br> BitcartCC Hosts</a></p> | <p><a href="lunanodeweb.md">LunaNode <br> Web-Wizard</a>*</p> | <p>- Low Difficulty<br>- BitcartCC Support (1)<br>- Lightning Network (2)</p> |
| Cost / Month                    |                                   Free                                   |                              $3.5                             |                                  BTC Accepted                                 |

_\*LunaNode Web-Wizard is a VPS solution, deployable from an easy-web interface._

| VPS Solutions                   |    1.    |            2.           |            3.            |             4.            |           5.           |                                   Why?                                  |
| ------------------------------- | :------: | :---------------------: | :----------------------: | :-----------------------: | :--------------------: | :---------------------------------------------------------------------: |
| <p>Business<br>(Self Setup)</p> | LunaNode | <p>Digital<br>Ocean</p> | <p>Amazon<br>AWS EC2</p> | <p>Microsoft<br>Azure</p> | <p>Google<br>Cloud</p> | <p>- Moderate Difficulty<br>- Docker Compose<br>- Lightning Network</p> |
| Cost / Month                    |   $3.5   |            $5           |            $9            |           $15-20          |           $7           |                             BTC Accepted (1)                            |

_- BitcartCC can also be deployed on any VPS that meets the minimal requirements._

| Developer Solutions                                                       |                                     |                                                              |                                                                                                     |
| ------------------------------------------------------------------------- | :---------------------------------: | :----------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: |
| <p>Developer<br>(Testing Setup)</p>                                       |            Manual Install           |                         Manual Build                         |                                            Hardware Build                                           |
| <p><strong>Not Recommended</strong><br><strong>For New Users</strong></p> | <p>Install From<br>Command Line</p> | <p><a href="manual.md">Build Without<br>Docker Image</a></p> | <p>ARM32v7<br><a href="raspberrypi/">Raspberry Pi</a><br><a href="hardware.md">BitcartCCBox</a></p> |

​
