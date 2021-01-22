# Blog application with NextJS and Contentful

This is a codebase for blog application that I build using NextJS with Contentful API

Live Demo: [https://nextjs-contentful-app.martindavid.now.sh](https://nextjs-contentful-app.martindavid.now.sh)

## Getting Started

### Clone this repo to your machine

```bash
$ git clone git@github.com:martindavid/nextjs-contentful-app.git nextjs-app
```


### Run Without Docker

#### Install dependencies

```bash
$ yarn install
```

Run it locally from [http://localhost:3000](http://localhost:3000):

```bash
$ CONTENTFUL_SPACE_ID=<space_id> CONTENTFUL_ACCESS_TOKEN=<access_token> yarn run dev
```
CONTENTFUL_SPACE_ID=ayjb08z5e2j6 CONTENTFUL_ACCESS_TOKEN=CFPAT-RBewPbMdxhCo5x3MAbvfwX2oG2ubSNjEn0TyDEdFTH8  yarn run dev

#### Deployment

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
$ now -e CONTENTFUL_SPACE_ID=<space_id> -e CONTENTFUL_ACCESS_TOKEN=<access_token>
```
now -e CONTENTFUL_SPACE_ID=ayjb08z5e2j6 -e CONTENTFUL_ACCESS_TOKEN=CFPAT-RBewPbMdxhCo5x3MAbvfwX2oG2ubSNjEn0TyDEdFTH8

### Run With Docker

Build it with docker:

```bash
# build
$ docker build -t nextjs-app .

# or, use multi-stage builds to build a smaller docker image (for deployment to production)
$ docker build -t nextjs-app -f ./Dockerfile.multistage .
```

Run it locally from [http://localhost:3000](http://localhost:3000):

```bash
$ docker run --rm -it \
    -p 3000:3000 \
    -e "CONTENTFUL_SPACE_ID=ayjb08z5e2j6" \
    -e "CONTENTFUL_ACCESS_TOKEN=CFPAT-RBewPbMdxhCo5x3MAbvfwX2oG2ubSNjEn0TyDEdFTH8" \
  next-app
```
docker run --rm -it -p 3000:3000 -e "CONTENTFUL_SPACE_ID=ayjb08z5e2j6 CONTENTFUL_ACCESS_TOKEN=CFPAT-RBewPbMdxhCo5x3MAbvfwX2oG2ubSNjEn0TyDEdFTH8"  nextjs-app


#### Deployment

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
# Deploy with docker image
$ now --docker -e CONTENTFUL_SPACE_ID=<contentful_space_id> -e CONTENTFUL_ACCESS_TOKEN=<contentful_access_token>
```



CONTENTFUL_SPACE_ID = ayjb08z5e2j6
CONTENTFUL_ACCESS_TOKEN = KE4o0CAGGbcpdpTwUzqetqGoDAsjqX7Ad4ow5r-vcJE
API_URL 

PU3-_37NHR3zQUaZUpmnuCf9yStLDDWEzxklzLQTRkw

PU3-_37NHR3zQUaZUpmnuCf9yStLDDWEzxklzLQTRkw

7kF7SpYaTUdprDhrL-li1ZQKRa90h7uO0tqVficqmUs


https://be.contentful.com/oauth/authorize?response_type=token&client_id=ayjb08z5e2j6&redirect_uri=$YOUR_APPS_REDIRECT_URL&scope=content_management_manage


npm run setup -- --spaceId 3nj81plfnxhg --deliveryToken vuR0U4l4Bx6Q59zonHQnFjWLDYRr8RWJIvS5wJVVCr0 --managementToken CFPAT-rDgQI9XQG20s4u1fZTWynSAmVLPapupSfmDV53xDs30