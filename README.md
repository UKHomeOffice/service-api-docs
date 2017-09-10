  
# Intro

This page is a summary of what to consider when documenting business services and corresponding APIs. it is not meant to be a comprehensive resource but more of  a  check list  to aid initial discussions on how to go about documenting services and APIs. As usual there are many tools out there and what works for you will very much depend on what's important to you. 

To achieve good interfaces,  business services must be described in details first (unless you are replacing existing interfaces which hopefully means you already have all documentation you need). Good business service description will make the task of writing the code a lot easier and good API documentation will help your customers to easily consume your interfaces.
 

# Business service description 

It will very much depend on in-house style but it is worth including the following minimum set in any service description.
  
 | Section | Descripton |
 |---------|------------|
 |Service name   | The name of the customer facing service as known to your customer.|
 | Service description | A basic description of what the service does, and what the deliverables and outcomes are.|
 | Service type   | Depends on the definition and structure known to you to build a service catalogue.|
 | Supporting services |   List any supporting services.|
 | Service owner(s) |A service owner is responsible for managing one or more services throughout their entire lifecycle|
 | Business impact| Describe of what would be the impact of not having this service available.|
 | Service level agreement| Agree on acceptable down time if any |
 | Comments | Any other text required to build the API.|
  
  
 # Good API description
  
 There are three aspects to consider when documenting an API
 
 #### What is for
 
 This includes 
 
 - A clear description of what the PAI call does
 - Detailed examples
 - list of parameters used on the call and their types and format
 - A sample response, including media type body, errors and warning
 
#### How to use 

 - Code examples for multiple languages
 - SDK examples (if SDKs are provided) showing how to access the resource/method utilising the SDK for their language
 - Interactive experiences (API Console) to try/test API calls 
 - FAQs
 
 #### Support
 
 - Links to additional resources (other examples, blogs, etc.)
 - Comments section where users can share/discuss code
 - Other support resources (forums, contact forms, etc.)
 
 
# Tooling

There are a number of tools to document service and API descriptions. Before making a decision, you need to consider your minimum must have features. Below is a short list to get you started.

Basic tooling requirements are:

- Re-use of currently avaible tools
- User friendly and easy to learn
- Easy to deploy and maintain
- Good presenation 


# To do 

- Include links to resources
- Expand on tooling




 

