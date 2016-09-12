# The Importance of APIs to the Internet of Things

Introduction
#1. About Octoblu
 We are an IoT Platform that allows you to connect APIs, Devices and people
 We support multiple protocols (MQTT, XMPP, CoAP, REST, Web Sockets, AMQP)
 We have already integrated 100s of APIs and can connect public and private APIs
 90% of our platform is open source
 We currently support 600 million messages a day over our platform
 You can build complex automations on our platform that can run 24/7 on container infrastructure in our Cloud
 Everything is a device (with UUID and Token)

#2. Why is IoT Important
- Allows for pervasive computing (computers embedded everywhere in the physical world)
- Create automations that tie apps and devices normally not meant to communicate
- Provides the ability to create context aware applications ()

#3. Current State of IoT
 - Focus is on Connecting Things and Creating Vertical Silos
 - Narrow Focus everybody is mainly concerned about collecting data

#3. The Future
IoT = Integration of Things
- Focus on connecting devices, software and people
- Using AI (Machine Learning) + IoT to create Intelligent Automation Agents that can
  monitor, learn about and control systems.

Demo

#4. Why APIs matter to IoT Platforms
 - Provide ability to glue and integrate services
 - Focus is on Application Interaction vs. Applications themselves
 - Allow developers to build context based applications that can interact with
   the physical world instead of purely through UI (proximity and location aware)

#5. Lessons Learned from an IoT Platform  Perspective
## 5.1 Versioning matters
  - Allow backwards compatibility with future versions
  - Communicate version changes and allow for version change detection
  - For IoT Platform it is hard to detect whether
## 5.2 State Matters (Push vs. Pull)
  - Provide ability to push state (web hooks, event streams)
  - Provide ability to pull state (REST)
## 5.3 Context Matters
 - Who is consuming your APIs?
Not every device will communicate over REST, devices have different form factors and computational power.
## 5.4 Security Matters
 - We provide transport layer encryption, provide a permissions model for you to secure access and allow you to encrypt
  messages with public private keys.
- We had to create a permissions model, allow for encryption, create virtual shadow credentials devices for our own API
## 5.5 Developers Matter
  - Give developers tools to quickly and easily setup and use your API
  - Provide meaningful non-trivial examples and documentation
  - Using known authentication standards make your api easier to adopt (Oauth, Basic Auth, Secure Tokens)

Questions

Contact
