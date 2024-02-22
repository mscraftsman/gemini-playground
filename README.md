# Gemini Playground

Playground to explore Google Gemini using various REST clients. The repository contains different approaches using the REST API of Google Gemini.

## Use .http files in Visual Studio 2022

While using Visual Studio one can use the .http file editor as a convenient way to explore an API. More information about .http files can be found in the official documentation [Use .http files in Visual Studio 2022](https://learn.microsoft.com/en-us/aspnet/core/test/http-files).

Open the project GeminiPlayground.csproj in Visual Studio 2022. The .http files contain HTTP calls to send requests to the different models provided by the Gemini API.

- gemini-pro.http contains requests using the Gemini Pro 1.0 model.
- gemini.pro-vision.http has requests against the Gemini Pro Vision 1.0 endpoints.

The .http files are using file-based environment variables. To get started you have to create a .env file in the project folder and add the following content to it. 

API_KEY=<your Gemini API key without quotes>

More details are described in the [.env files](https://learn.microsoft.com/en-us/aspnet/core/test/http-files?view=aspnetcore-8.0#env-files) paragraph.

All API requests are based on the [Quickstart: Get started with Gemini using the REST API](https://ai.google.dev/tutorials/rest_quickstart).
