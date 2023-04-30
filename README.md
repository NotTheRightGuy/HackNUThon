# Midway 

## Bi-Directional Integration Middleware


Midway is a backend middleware application that facilitates bi-directional integration between two separate systems supporting REST, SOAP, or GraphQL communication with compatibility between them. It can handle throttling, data transformation, security, and protocol conversion.

## Features

- Bi-directional integration between two separate systems
- Support for REST, SOAP, and GraphQL communication
- Throttling to manage traffic flow
- Data transformation to ensure compatibility
- Security measures to protect sensitive data
- Protocol conversion to ensure seamless integration

## How it works

Midway acts as a mediator between two separate systems, translating and managing communication between them. It ensures compatibility by handling data transformation and protocol conversion, and can also manage traffic flow through throttling. Additionally, it provides security measures to protect sensitive data.

Our website allows you to receive responses from APIs in the format that you want. If you post to any of the APIs we support, our website will take care of formatting the response according to your preferences. This allows you to easily consume data from multiple sources without having to worry about compatibility or conversion.

In addition, we support multiple databases for different data sources. This means that you can easily switch between different databases depending on your needs, without having to worry about data loss or compatibility issues. Our website handles all of the data transformation and conversion for you, so that you can focus on your business goals.  


=======

## Getting started

1. Clone this repository
2. Install dependencies with `npm install`
3. Configure your integration endpoints in `config.json`
4. Start the application with `npm start`

## Configuration

Midway requires configuration in order to connect to the systems you wish to integrate. Configuration options can be found in `config.json`, and include the following:

- `source`: The source system's configuration, including endpoint URL, authentication credentials, and data format.
- `destination`: The destination system's configuration, including endpoint URL, authentication credentials, and data format.

- `throttling`: Throttling configuration, including rate limits and time windows.

- `transformation`: Data transformation configuration, including data mapping and formatting.
- `security`: Security configuration, including encryption and tokenization.
- `protocol`: Protocol conversion configuration, including supported protocols and format conversion.

## Contributing

If you wish to contribute to Midway, please fork this repository and submit a pull request with your changes.

## Team name:
- Bits N' Bytes

## Team Members:
- Janmejay Chatterjee
- Prem Patel
- Devvrat Singh


## License

Midway is licensed under the [MIT License](https://opensource.org/licenses/MIT).
