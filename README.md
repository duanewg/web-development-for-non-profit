<p align="center">
<!--img src="https://place-hold.it/600x200" alt="Place Holder Image"/-->
<img src="assets/aws.jpeg" alt="Amazon Web Services" />
</p>

# Non Profit Website Development  
Designed, developed, and deployed a static website for a non profit organization that did not have a web presence.  HTML, CSS, & Javascript were used for development and the website was hosted in AWS.  The website provided users with an organization overview, services offered, upcoming events, contacts, and program partners.


## Environments and Technologies Used

- HTML
- CSS
- JavaScript
- Visual Studio Code
- Amazon S3
- Amazon CloudFront

## High-Level Deployment and Configuration Steps

#### S3
- Create a bucket
- Enable static website hosting
- Edit Block Public Access settings
- Add a bucket policy that makes your bucket content publicly available
- Configure an index document
- Configure error documents

#### Certificate Manager
- Request a certificate
- Enter domain name
- Set validation method to DNS
- Set key algorithim
- Validate domain ownership

#### CloudFront
- Create Distribution
- Configure Origin using S3 bucket endpoint
- Set Viewer Protocol Policy for HTTP/HTTPS
- Configure Alternate Domain Name (CNAME)
- Choose Custom SSL Certificate

<h2>Screenshot</h2>

<p>
<img src="assets/nonprofit-web-screenshot.png" height="80%" width="80%" alt="Screenshot"/>
</p>
