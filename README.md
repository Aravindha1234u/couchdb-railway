# CouchDB - Railway Template

This example deploys a self-hosted version of [CouchDB](https://couchdb.apache.org/). 

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/eRC98l?referralCode=HT4TtK)

## What is CouchDB?
CouchDB is an open source NoSQL database that stores your data with JSON documents, which you can access via HTTP. It allows you to index, combine, and transform your documents with JavaScript.

## Why use CouchDB?
Apache CouchDB ™ lets you access your data where you need it. The Couch Replication Protocol is implemented in a variety of projects and products that span every imaginable computing environment from globally distributed server-clusters, over mobile phones to web browsers.

Store your data safely, on your own servers, or with any leading cloud provider. Your web- and native applications love CouchDB, because it speaks JSON natively and supports binary data for all your data storage needs.

The Couch Replication Protocol lets your data flow seamlessly between server clusters to mobile phones and web browsers, enabling a compelling offline-first user-experience while maintaining high performance and strong reliability. CouchDB comes with a developer-friendly query language, and optionally MapReduce for simple, efficient, and comprehensive data retrieval.

[Learn more](https://couchdb.apache.org/)

## ✨ Services

- CouchDB

## 💁‍♀️ How to use

- Click the Railway button 👆
- Add the required environment variables to your Railway project
- If you need to make any changes to the configuration, edit `custom.ini` in the `couchdb` folder and commit the changes
- If you need Add your application, then make sure to create a folder and copy the file inside Docker with all dependencies installed. Check `Dockerfile` for more details
- To Expose CouchDB in different ports, Add a new environment variable `COUCHDB_CLUSTER_PORT_NUMBER` and set the value to the port number you want to expose. Update the `PORT` value in railway to the same port number.
- Deploy
- You can access the CouchDB Web UI by opening your web browser and navigating to Railway's public URL with path `_utils` something like this `https://<project-name>.railway.dev/_utils/`. You should be able to see the CouchDB Dashboard.
- Examples Folder has a sample code to connect to CouchDB and perform CRUD operations. You can use this as a reference to build your application.


## 📝 Notes

- Source repo: https://github.com/apache/couchdb
- Docs: https://docs.couchdb.org/en/stable/
- Docker Image: https://hub.docker.com/r/bitnami/couchdb