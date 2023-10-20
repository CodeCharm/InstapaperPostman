# InstapaperPostman
An importable Postman collection and environment that can be used to invoke API calls to Instapaper.com. Primarily intended for incidental use, and with a Premium subscription which is not required.

This project is not affiliated with Instapaper.com. It is not endorsed by Instapaper. It is a personal project I created to better understand how to invoke the API with its OAuth1 authorization process.

It is also not affiliated with Postman.

## How to use

Clone the repository to your workstation.

Import the collection and the environment files into Postman. See https://learning.postman.com/docs/designing-and-developing-your-api/importing-an-api/ for information about importing collections. Besides the Import buttons on the Collections panel and the Environments panel, you can also drag-and-drop the JSON files directly onto the panels.

You will need to select the `Instapaper` environment as the active environment to get the most use out of the collection. Some of the test scripts will store values into the environment, and most of the APIs expect to use an environment variable.

If you would like to use the Full API, you will need to request a consumer_token from Instapaper. See https://www.instapaper.com/api/full for details.

When you get the OAuth Consumer ID and the OAuth Consumer Secret from Instapaper, copy the values into the Instapaper environments `OAuth1:Consumer_ID` and `OAuth1:Consumer_Secret` variables, in the Current Value column.
