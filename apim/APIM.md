# API Management (APIM)

## <a name="APIM"></a> APIM key components

1. [Developer Portal](#developer-portal) - Developer Portal
2. [Monetization](#monetization) - Monetization
3. [Gateway](#gateway) - Gateway
4. [API Store](#api-store) - API Store
5. [Security](#security-policies) - Security & Policies
6. [Monitoring & Logs](#monitoring-logs) - Monitoring & Logs
7. [Reports & Analytics](#reports-analytics) - Reports & Analytics
8. [SLA](#SLA) - Service Level Agreement

## <a name="developer-portal"></a> Developer Portal

Provides a developer portal for developers to learn about, test, and use APIs. The developer portal typically includes
documentation, such as API reference guides and tutorials, a sandbox environment for testing API requests, support
resources such as a knowledge base and community forums, SDK

1. Documentation
2. Sandbox environment
3. Support resources
4. SDKs and code samples
5. Developer registration and onboarding
6. API analytics
7. API management and governance
8. Monetization
9. Lifecycle management

for more detail see:
[Developer Portal](/apim/components/developer-portal.md)


## <a name="monetization"></a> Monetization

Monetizes APIs through billing and pricing, which involves setting up billing plans and pricing tiers for API usage,
payment gateway integration, which involves integrating with payment gateways such as Stripe or PayPal to process
payments, and revenue management, which involves generating invoices, reconciling payments, and managing taxes and
currency conversions.

- Billing and pricing
- Payment gateway integration
- Revenue management
- Partner management
- Legal and compliance

for more detail see:
[Monetization](/apim/components/monetization.md)

## <a name="gateway"></a> Gateway

A proxy gateway is a type of API gateway that acts as an intermediary between API consumers and API providers. It
receives requests from API consumers and forwards them to the appropriate API provider.

1. Request Routing
2. Protocol Translation
3. Transformation
4. Security
5. Load Balancing
6. Caching
7. Logs & Metrics

for more detail see:
[Gateway](/apim/components/gateway.md)

## <a name="api-store"></a> API Store

API Store is a component of an API management platform that provides a catalog of APIs for developers to browse,
discover, and subscribe to. It is typically implemented as a web portal or a developer portal, and it serves as a
centralized location for developers to find and learn about the APIs that are available to them.

1. Catalog of APIs
2. Search and filtering tools
3. Documentation and tutorials
4. Test tools and consoles
5. Subscription and billing management
6. Support resources

## <a name="security-policies"></a> Security & Policies

Secures APIs by providing authentication mechanisms to verify the identity of API clients, authorization mechanisms to
determine which clients are allowed to access which resources, and SSL/TLS termination to encrypt communication between
clients and the API gateway.
Policies

1. Authentication
2. Authorization
3. SSL/TLS termination

## <a name="monitoring-logs"></a> Monitoring & Logs

Monitors and analyzes API usage through request logging, which captures information about each API request and response,
performance metrics, which measure the performance of the API gateway and backend services, and alerting, which sends
notifications when certain thresholds or conditions are met.

1. Registration
2. Aggregation
3. Monitoring

for more detail see:
[Monitoring & Logs](/apim/components/monitoring-logs.md)

## <a name="reports-analytics"></a> Reports & Analytics

Once data is collected, it will be organized using tools such as graphs and tables. The process of organizing this data
is called reporting. Analytics, on the other hand, is the process of taking the organized data and analyzing it in order
to gain valuable insights on how businesses can improve their performance.


1. Users
2. Actions
3. Third Party
4. Integration

for more detail see:
[Reports & Analytics](/apim/components/reports-analytics.md)

## <a name="sla"></a> SLA

A service level agreement (SLA) is a critical contract between a service provider and a consumer, outlining various objectives, obligations and actions concerning API services. It sets the standards for Quality of Service (QoS), which are agreed upon and measured based on the agreement. SLA monitoring is essential for identifying key performance characteristics of the API, evaluated under Service Level Objectives (SLO). The core aim of SLA monitoring within the API ecosystem is to track and compare the agreed SLOs with the actual performance. This process is vital for maintaining long-term, trust-based relationships between the involved parties.

In the realm of API management, several key performance metrics are curcial for upholding the terms of an SLA contract between providers and consumers. These include:


1. **Latency**: measure the time taken for an API request to receive a response. Low latency is crucial for ensuring a swift and efficient user experience. For example, optimizing an image processing API to reduce latency below 500ms.

2. **Response Time**: total time from when a request is made until the complete response is received by the client. It includes not only the travel time(latency) but also the time the server takes to process the request and generate a response. 

3. **Service Uptime**: indicate the availability of the API service. High uptime percentages are essential for reliable access to the service. For instance, an API with 99.99& availability is down for no more than 8.76 hours annualy. Considering monthly, the calculation would be as followed:

60 min x 24h x 30 days = 43200 minutes in a month

This means no more than 4 minutes of unexepcted downtime per month. 

4. **Throughput**: refer to the number of requests an API can handle within a given time frame. It's vital for assessing the API's capacity to manage high loads without compromising performance. 

5. **Error Rate**: Monitoring the frequency of failed API requests helps in maintaining service reliability and troubleshooting issues promptly.

6. **TCP Connection**: time taken to establish a TCP connection with the API's server. 

    Scenario: Real-Time Stock Trading Platform

    **API Role**: The platform's API retrieves real-time stock price data from the stock exchange server.

    **Importance of Fast TCP Connection**: When a trader places an order, even a millisecond's delay in fetching the latest stock prices can impact the trade's outcome, especially in high-frequency trading where decisions are made in fractions of a second.

    **TCP Connect Metric**: Suppose the objective is to have a TCP connection established in less than 50 milliseconds.
   
    **Impact**: Achieving this metric ensures that when the platform sends a request to the stock exchange API, the initial connection is established swiftly, enabling real-time data retrieval without significant delays. This speed is crucial for traders who rely on up-to-the-moment information for their trading decisions.

7. **DNS Lookup**: refer to the process of converting a domain name (like 'www.example.com') into an IP address that computers use to identify each others on the network. 

Scenario: Consider a popular video streaming service, which users access through its website or app.

**API Role**: When a user selects a video to watch, the app makes a request to the streaming service's API. This request starts with a DNS lookup to find the server's IP address.

**DNS Lookup Objective**: Suppose the goal is to have DNS lookups completed in less than 20 milliseconds.

**Importance of Speed**: In a streaming service, users expect videos to start playing almost instantly after selection. Any delay, even a few seconds, can lead to frustration and a poor user experience.

**Impact of Fast DNS Lookup**: Achieving this DNS lookup speed ensures that the process of translating the domain to an IP address is swift. This efficiency is crucial because it's the first step in establishing a connection with the API server. Once the IP address is quickly resolved, the rest of the process (like establishing a connection and starting data transfer) can proceed without unnecessary delay.

**User Experience**: For the user, this translates to a near-instantaneous start of video playback after they hit play, contributing to a seamless and enjoyable viewing experience

**SSL Handshake**

**Download Time**

**Upload Time** 

**Processing Time**

