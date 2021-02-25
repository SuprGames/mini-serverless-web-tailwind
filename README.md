# Mini Serverless Web Tailwind

Minimal Serverless project for a Static Web in S3 using Tailwind-CSS

## Considerations
The project assumes you have installed NPM and Serverless Framework in your Global

## Some basic explanations
We suppose you know about Tailwind, but still we have add a couple of nice to have in the css/tailwind.css file:

* Basic Tailwind imports
* Shadow text classes (4 classes with different sizes of Text shadows)
* Example of a font import `you-blockhead.ttf` with a new class called `primary-text`
* An example of basic styling of the body to show how to create your own

## Instructions

* Install the project dependencies: `npm i`
* Build the project with: `npm run build`
* Run locally the project with: `npm run start`

Go to http://127.0.01:8000 and voilà!

## Serverless

Make sure you have updated the template values:

- In `serverless.yml` file:
  * ${YOUR_ORGANIZATION}
  * ${YOUR_APP}
  * ${YOUR_SERVICE_NAME}
  * ${YOUR_BUCKET_NAME}

- In s3-bucket-policy:
  * ${YOUR_BUCKET_NAME}

Once the values are updated then run `npm i` to initialise all

Happy coding :)

## Wait a minute I just come for the Basic Tailwind Template!
To have the basic Tailwind Template simply remove `serverless.yml` file, the `serverless-finch` import from package.json and the deploy script.

Or even easier, just use this guy:

https://github.com/SuprGames/mini-web-tailwind