# Instructions
The first step we have to do is to build the image. This image uses the official image of metabase as base and adds the oracle driver to be able to connect with Oracle databases.
To build the image you have to run the following command:

`docker build -t metabase-oracle .`

The next step is to run the image

`docker run -d -p 3000:3000 –-name metabase metabase-oracle`

This command will run metabase and make it available in port `3000`
