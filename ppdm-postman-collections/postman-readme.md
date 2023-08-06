# Getting Started with PPDM REST API using Postman Collections

Here is the a blog post for detailed information https://www.dell.com/community/Blogs/Getting-Started-with-PPDM-REST-API-using-Postman-Collections/ba-p/8424744


## Prerequisites:

Before embarking on your journey to Dell PPDM automation using Postman, ensure that you have the following prerequisites in place:

* Functional Dell PowerProtect Data Manager (PPDM) Instance: Ensure that you have a fully operational PPDM instance accessible via a designated URL.

* Postman Application: Download and install the Postman application—a versatile and industry-standard API testing and automation tool, offered at no cost.

## Step-by-Step

1. Obtain PPDM API Access Credentials:
To initiate interactions with the PPDM API, the first step necessitates the acquisition of API access credentials, namely a username and password, from your PPDM instance. These credentials will serve as the authentication mechanism for your API requests.

2. Import the Postman Collection and Environment:
Begin by downloading the pre-constructed Postman collection from GitHub repository. Import the collection into Postman by selecting the "Import" button and subsequently importing both the collection and environment files.

3. Configure Environment Variables:
Effectively configuring environment variables tailored to your specific PPDM environment is imperative. Variables encompassing PPDM server IP addresses, user credentials, passwords, vCenter details, and any other pertinent parameters should be updated. Review the list of variables and ensure each is appropriately amended to reflect your environment.

4. Navigate through the Collection:
Within the imported Postman collection, an array of API endpoints awaits your exploration. Organised into distinct folders, each folder corresponds to a unique resource type. These folders house an assortment of endpoints pertinent to the given resource type. Importantly, these API calls are pre-configured with requisite parameters, headers, authorization, filters, and request bodies.

5. Execute Requests:
Equipped with correctly configured environment variables and headers, you are poised to execute individual API requests from the collection. Your journey begins with the login request, a pivotal step in securing an authentication token. Subsequent requests hinge on the presence of this authentication token, thus reinforcing its significance. Gradually, you will advance to more intricate operations, such as initiating backups or orchestrating restores.

## Use Cases

![](images/ppdm-postman.PNG)



## Contributions

I welcome contributions from the community! If you have additional examples, improvements, or fixes, please feel free to submit a pull request.


## Author

* **Raghava Jainoje** - [rjainoje](https://github.com/rjainoje)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details