# Pod Point Technical Test RESTful API Specifications

This is a Stoplight Studio RESTful API specification we use throughout some of our technical tests.

## Installation

You can install this on any of our technical test re-using the same RESTful API implementation.

```bash
git clone git@github.com:Pod-Point/tech-test-api-specs.git reference
```

If you're an applicant and landed here, you shouldn't need to worry about pulling this manually, it should automatically be available for you within `/reference` after running `make start`.

## How to use it

You can use [Stoplight Studio](https://stoplight.io/studio) in order to browse the API documentation within the `/reference` folder you just created by cloning this repository:

![Open Existing Folder](../docs/stoplight-open-folder.png)

You can also import the Open API v3 file located under `/reference/pod-point/openapi.yml` into [Postman](https://www.postman.com/downloads/) in order to automatically [create a Collection](https://learning.postman.com/docs/postman/collections/importing-and-exporting-data/#collections). Once imported, make sure your Collection variables (mainly `baseUrl`) are accurate.

---

<img src="https://d3h256n3bzippp.cloudfront.net/pod-point-logo.svg" align="right" />

Travel shouldn't damage the earth 🌍

Made with ❤️&nbsp;&nbsp;at [Pod Point](https://pod-point.com)
