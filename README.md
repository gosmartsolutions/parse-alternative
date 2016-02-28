# Open Source Parse Alternative
With the recent announcement from Facebook that Parse will be shutting down, we wanted to provide open source alternatives to Parse. It seems lately that we are hearing weekly announcements about another API shutting down. We ourselves have been bitten by this in the past. This is why we believe that if you can easily roll an open source or affordable solution on your own server, you should.

We will be accumulating and updating a list here of open source options we have used and tested as well as providing example scripts on how you can communicate with the API's.

#DreamFactory
DreamFactory a REST API platform built with the Laravel framework. The nice thing about DreamFactory is that it automatically creates API endpoints for most of the databases used, plus for email, file storage and push notifications. It is super easy to connect to data sources and secure your APIs with user & group permissions.

We have used DreamFactory for multiple projects. We have connected to Amazon RDS for databases and even Amazon S3 for file and image uploading. Dreamfactory is fairly easy to install on both an AWS EC2 instance as well as Digital Ocean.

We will be providing some sample API scripts soon that demonstrate how to connect & read/add/update data to a database and upload images to S3 using the DreamFactory API.

#Baasbox
From the Baasbox website: "Build your app in minutes. No vendor lock-in Deploy BaasBox anywhere you like with SDKs for iOS, Android and Javascript". We looked at Baasbox and it looks promising. It doesn't appear to be as seasoned as DreamFactory but is really easy to install and has the core featured needed for most mobile apps. We will be testing Baasbox more extensively in the near future.

#Hook
From the hook website "Hook is a restful, extendable backend as a service that provides instant backend to develop sites and apps faster, with dead-simple integration with ios, android, javascript and more."

We haven't had a chance to test Hook yet but plan to very soon. It looks very promising and the fact that it is written is PHP, should make it easy to get setup on most any host or server. It has user authentication built right in and their Hooks features look really useful.

#Parse Server
Parse themselves released an open source version of the service making it easy for those of you who currently use Parse to migrate. From Parse: "The open source Parse Server makes it possible to serve the Parse API from any infrastructure that can host Node.js applications. Parse Server provides a way for you to keep your application running without major changes in the client-side code, once you have your data in your own database."

If your app is currently running on Parse, using the open source Parse server might be your best option. 

#HIRE US TO HELP SETUP YOUR OWN REST API SYSTEM
Do you like the idea of rolling your own REST api system but need help getting started?
[CONTACT US HERE](http://www.gosmartsolutions.com/#contact) and let us know what your needs are and we will get back to you quickly.


