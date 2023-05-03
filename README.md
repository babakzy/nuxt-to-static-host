# nuxt-to-static-host
## Github action for deploying Nuxt.js app on static host using FTP
This action uses Nuxt static website generation to generate a static website (note that this is not possible with server-side rendering apps)

 - Tested on Nuxt 3
 - Uses FTP (SamKirkland/FTP-Deploy-Action@v4.3.4)
 - Deploys .output/public folder to the root directory of the host
