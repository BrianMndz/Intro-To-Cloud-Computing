# Hybrid Multi-cloud, Microservices and serverless

## Hybrid Multi-cloud

Hybrid cloud: connects an organization's on-premise private cloud and third-party
public cloud into a single infrastructure for running the organization's apps.

Multi-cloud: strategy mix (public, private and managed). email, CRM and infrastructure from different providers and get the best approach.

### Use-case: cloud scaling

on-premise infrastructure, to scale-up on response when it is more required and less when is freed.
Compose cloud: multiple cloud environments. I.E: UI, API and frameworks can move the capabilities over to a cloud platform of their choice.

Modernization: most airlines have mobile applications. Resversation system on prem, backed the app on public cloud. User experience is better. Airlines takes advantage of cloud to recommend.

Data and IA: Lots of historical data. Unplanned maintenance for example. Legacy data they have and connect to ML to get prediction.

Prevent to specific vender and can move onto another vendor if it's needed.

## Microservices

Own containers.
API <-> Event Streaming <-> message brokers. Multiple developers working independently. Dfferent stacks and runtime enviroment. Independent scaling.

In the past: app is monolithic app. No line of code from scratch. Ecosystem of code to integrate on apps.

breakdown features into differenten functions. Cointainer in the distribution. Metadata feeds a microservice. Service discovery. Using analytics to create better recomendations.

## Serverless Computing

Offloads responsibility from common infrastructure management (scaling, scheduling, patching and provisioning).

Serverless does not mean there is no servers. Only management is removed from their users.

No provisioning of servers & runtimes. Runs code only on-demand. Pay only for resources used.

Abstract infrastructure. away from developers. Code executed as individual function.
IBM cloud function. AWS Lambda. Microsoft azure.

Fit: Ensure the patterns. Good fit: short running stateless function. seasonal workloads. Production volumetricdata. event-based processing.

Data and event processing, IoT, microservices and mobile backend.

Well suited to working with: text, audio, image, video.
Task: data enrichment, transformation, validation, pdf processing, audio normalization, thumbnail gen. video transcoding.

Challenges: scale up/down, but simpler in other tradicional server environment.

## Summary: 

Hybrid Multicloud is a cloud adoption strategy that makes it possible for public clouds, private clouds, and on-premises IT to interoperate seamlessly while leveraging the best cloud-based services from different public cloud providers.

Microservices architecture is an approach in which an application is built as a collection of loosely coupled and independently deployable components or services, leading to efficient development, maintenance, and upgradation cycles.

Serverless Computing is an approach to computing that offloads responsibility for common infrastructure management tasks for application runtimes to cloud providers, allowing developers to focus their time and effort on development and testing, and not have to worry about provisioning, maintaining and scaling compute resources.



