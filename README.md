# Awesome Keycloak [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# [<img src="https://www.keycloak.org/resources/images/logo.svg">](https://github.com/thomasdarimont/awesome-keycloak)

> Carefully curated list of awesome Keycloak resources.

A curated list of resources for learning about the Open Source Identity and Access Management solution Keycloak. 
Contains books, websites, blog posts, links to github Repositories.  

# Contributing
Contributions welcome. Add links through pull requests or create an issue to start a discussion.
[Please refer to the contributing guide for details](CONTRIBUTING.md).

# Contents

* [General](#general)
  * [Documentation](#docs)
    * [Keycloak Website](http://www.keycloak.org)
    * [Current Documentation](http://www.keycloak.org/documentation.html)
    * [Archived Documentation](http://www.keycloak.org/documentation-archive.html)
  * [Mailing Lists](#mailing-lists)
    * [User Mailing List](#user-mailing-list)
    * [Developer Mailing List](#dev-mailing-list)
    * [Mailing List Search](#mailing-list-search)
* [Books](#books)
* [Articles](#articles)
* [Talks](#talks)
* [Presentations](#presentations)
* [Video Playlists](#video-playlists)
* [Community Extensions](#community-extensions)
* [Integrations](#integrations)
* [Themes](#themes)
* [Docker](#docker)
* [Deployment Examples](#deployment-examples)
* [Example Projects](#example-projects)
* [Benchmarks](#benchmarks)
* [Help](#help)
* [Commercial Offerings](#commercial-offerings)
* [Miscellaneous](#miscellaneous)

# General

## Documentation

*  [Keycloak Website](http://www.keycloak.org/)
*  [Current Documentation](http://www.keycloak.org/documentation.html)
*  [Archived Documentation](http://www.keycloak.org/documentation-archive.html)
*  [Product Documentation for Red Hat Single Sign-On](https://access.redhat.com/documentation/en/red-hat-single-sign-on/)

## Discussion Groups and Mailing Lists
*  [Keycloak Users Google Group](https://groups.google.com/forum/#!forum/keycloak-user)
*  [Keycloak Developers Google Group](https://groups.google.com/forum/#!forum/keycloak-dev)
*  [Keycloak Discourse Group](https://keycloak.discourse.group/)
*  [Inactive - Keycloak Developer Chat](https://keycloak.zulipchat.com)
*  [Inactive - User Mailing List](https://lists.jboss.org/mailman/listinfo/keycloak-user)
*  [Inactive - Developer Mailing List](https://lists.jboss.org/mailman/listinfo/keycloak-dev)
*  [Mailing List Search](http://www.keycloak.org/search)
*  [Keycloak Subreddit](https://www.reddit.com/r/keycloak)
*  [GitHub Discussions](https://github.com/keycloak/keycloak/discussions)
*  [CNCF Slack](https://slack.cncf.io/), [#keycloak](https://cloud-native.slack.com/archives/C056HC17KK9), [#keycloak-dev](https://cloud-native.slack.com/archives/C056XU905S6)

## Books
* [Keycloak - Identity and Access Management for Modern Applications](https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications/9781800562493)
* [Keycloak - Identity and Access Management for Modern Applications - Second Edition](https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications-second-edition/9781804616444)

## Articles
*  [How to get Keycloak working with Docker](https://www.ivonet.nl/2015/05/23/Keycloak-Docker/)
*  [Single-Sign-On for Microservices and/or Java EE applications with Keycloak SSO](http://www.n-k.de/2016/06/keycloak-sso-for-microservices.html)
*  [Keycloak Admin Client(s) - multiple ways to manage your SSO system](http://www.n-k.de/2016/08/keycloak-admin-client.html)
*  [How to get the AccessToken of Keycloak in Spring Boot and/or Java EE](http://www.n-k.de/2016/05/how-to-get-accesstoken-from-keycloak-springboot-javaee.html)
*  [JWT authentication with Vert.x, Keycloak and Angular 2](http://paulbakker.io/java/jwt-keycloak-angular2/)
*  [Authenticating via Kerberos with Keycloak and Windows 2008 Active Directory](http://matthewcasperson.blogspot.de/2015/07/authenticating-via-kerberos-with.html)
*  [Deploying Keycloak with Ansible](https://adam.younglogic.com/2016/01/deploying-keycloak-via-ansible/)
*  [Easily secure your Spring Boot applications with Keycloak](https://developers.redhat.com/blog/2017/05/25/easily-secure-your-spring-boot-applications-with-keycloak/)
*  [How Red Hat re-designed its Single Sign On (SSO) architecture, and why](https://developers.redhat.com/blog/2016/10/04/how-red-hat-re-designed-its-single-sign-on-sso-architecture-and-why/)
*  [OAuth2, JWT, Open-ID Connect and other confusing things](http://giallone.blogspot.de/2017/06/oath2.html)
*  [X509 Authentication with Keycloak and JBoss Fuse](https://sjhiggs.github.io/fuse/sso/x509/smartcard/2017/03/29/fuse-hawtio-keycloak.html)
*  [Running Keycloak on OpenShift 3](https://medium.com/@sbose78/running-keycloak-on-openshift-3-8d195c0daaf6)
*  [Introducing Keycloak for Identity and Access Management](https://www.thomasvitale.com/introducing-keycloak-identity-access-management/)
*  [Keycloak Basic Configuration for Authentication and Authorisation](https://www.thomasvitale.com/keycloak-configuration-authentication-authorisation/)
*  [Keycloak on OpenShift Origin](https://medium.com/@james_devcomb/keycloak-on-openshift-origin-ee81d01dac97)
*  [Identity Management, One-Time-Passwords and Two-Factor-Auth with Spring Boot and Keycloak](http://www.hascode.com/2017/11/identity-management-one-time-passwords-and-two-factor-auth-with-spring-boot-and-keycloak/)
*  [Keycloak Identity Brokering with Openshift](https://developers.redhat.com/blog/2017/12/06/keycloak-identity-brokering-openshift/)
*  [OpenID Connect Identity Brokering with Red Hat Single Sign-On](https://developers.redhat.com/blog/2017/10/18/openid-connect-identity-brokering-red-hat-single-sign/)
*  [Authentication & user management is hard](https://eclipsesource.com/blogs/2018/01/11/authenticating-reverse-proxy-with-keycloak/)
*  [Securing Nginx with Keycloak](https://edhull.co.uk/blog/2018-06-06/keycloak-nginx)
*  [Secure kibana dashboards using keycloak](https://aboullaite.me/secure-kibana-keycloak/)
*  [Configuring NGINX for OAuth/OpenID Connect SSO with Keycloak/Red Hat SSO](https://developers.redhat.com/blog/2018/10/08/configuring-nginx-keycloak-oauth-oidc/)
*  [Keycloak Clustering Setup and Configuration Examples](https://github.com/fit2anything/keycloak-cluster-setup-and-configuration)
*  [MicroProfile JWT with Keycloak](https://kodnito.com/posts/microprofile-jwt-with-keycloak/)
*  [Keycloak Essentials](https://medium.com/keycloak/keycloak-essentials-86254b2f1872)
*  [SSO-session failover with Keycloak and AWS S3](https://medium.com/@georgijsr/sso-session-failover-with-keycloak-and-aws-s3-e0b1db985e12)
*  [KTOR and Keycloak: authentication with OpenId](https://medium.com/slickteam/ktor-and-keycloak-authentication-with-openid-ecd415d7a62e)
* [Keycloak: Core concepts of open source identity and access management](https://developers.redhat.com/blog/2019/12/11/keycloak-core-concepts-of-open-source-identity-and-access-management)
* [Writing Keycloak Extensions: Key Concepts and Anti-Patterns](https://www.zone2.tech/blog/writing-keycloak-extensions-key-concepts-and-anti-patterns)
* [Who am I? Keycloak Impersonation API](https://blog.softwaremill.com/who-am-i-keycloak-impersonation-api-bfe7acaf051a)
* [Setup Keycloak Server on Ubuntu 18.04](https://medium.com/@hasnat.saeed/setup-keycloak-server-on-ubuntu-18-04-ed8c7c79a2d9)
* [Getting started with Keycloak](https://robferguson.org/blog/2019/12/24/getting-started-with-keycloak/)
* [Angular, OpenID Connect and Keycloak](https://robferguson.org/blog/2019/12/29/angular-openid-connect-keycloak/)
* [Angular, OAuth 2.0 Scopes and Keycloak](https://robferguson.org/blog/2019/12/31/angular-oauth2-keycloak/)
* [Keycloak, Flowable and OpenLDAP](https://robferguson.org/blog/2020/01/03/keycloak-flowable-and-openldap/)
* [How to exchange token from an external provider to a keycloak token](https://www.mathieupassenaud.fr/token-exchange-keycloak/)
* [Building an Event Listener SPI (Plugin) for Keycloak](https://dev.to/adwaitthattey/building-an-event-listener-spi-plugin-for-keycloak-2044)
* [Keycloak user migration – connect your legacy authentication system to Keycloak](https://codesoapbox.dev/keycloak-user-migration/)
* [Keycloak Authentication and Authorization in GraphQL](https://medium.com/@darahayes/keycloak-authentication-and-authorization-in-graphql-ad0a1685f7da)
* [Kong / Konga / Keycloak: securing API through OIDC](https://github.com/d4rkstar/kong-konga-keycloak)
* [KeyCloak: Custom Login theme](https://codehumsafar.wordpress.com/2018/09/11/keycloak-custom-login-theme/)
* [Keycloak: Use background color instead of background image in Custom Login theme](https://codehumsafar.wordpress.com/2018/09/21/keycloak-use-background-color-instead-of-background-image-in-custom-login-theme/)
* [How to turn off the Keycloak theme cache](https://keycloakthemes.com/blog/how-to-turn-off-the-keycloak-theme-cache)
* [How to add a custom field to the Keycloak registration page](https://keycloakthemes.com/blog/how-to-add-custom-field-keycloak-registration-page)
* [How to setup Sign in with Google using Keycloak](https://keycloakthemes.com/blog/how-to-setup-sign-in-with-google-using-keycloak)
* [How to sign in users on Keycloak using Github](https://keycloakthemes.com/blog/how-to-sign-in-users-on-keycloak-using-github)
* [Extending Keycloak SSO Capabilities with IBM Security Verify](https://community.ibm.com/community/user/security/blogs/jason-choi1/2020/06/10/extending-keycloak-sso-capabilities-with-ibm-secur)
* [AWS SAML based User Federation using Keycloak](https://medium.com/@karanbir.tech/aws-connect-saml-based-identity-provider-using-keycloak-9b3e6d0111e6)
* [AWS user account OpenID federation using Keycloak](https://medium.com/@karanbir.tech/aws-account-openid-federation-using-keycloak-40d22b952a43)
* [How to Run Keycloak in HA on Kubernetes](https://blog.sighup.io/keycloak-ha-on-kubernetes/)
* [How to create a Keycloak authenticator as a microservice?](https://medium.com/application-security/how-to-create-a-keycloak-authenticator-as-a-microservice-ad332e287b58)
* [keycloak.ch | Installing & Running Keycloak](https://keycloak.ch/keycloak-tutorials/tutorial-1-installing-and-running-keycloak/)
* [keycloak.ch | Configuring Token Exchange using the CLI](https://keycloak.ch/keycloak-tutorials/tutorial-token-exchange/)
* [keycloak.ch | Configuring WebAuthn](https://keycloak.ch/keycloak-tutorials/tutorial-webauthn/)
* [keycloak.ch | Configuring a SwissID integration](https://keycloak.ch/keycloak-tutorials/tutorial-swissid/)
* [Getting Started with Service Accounts in Keycloak](https://medium.com/@mihirrajdixit/getting-started-with-service-accounts-in-keycloak-c8f6798a0675)
* [Building cloud native apps: Identity and Access Management](https://dev.to/lukaszbudnik/building-cloud-native-apps-identity-and-access-management-1e5m)
* [X.509 user certificate authentication with Red Hat’s single sign-on technology](https://developers.redhat.com/blog/2021/02/19/x-509-user-certificate-authentication-with-red-hats-single-sign-on-technology)
* [Grafana OAuth with Keycloak and how to validate a JWT token](https://janikvonrotz.ch/2020/08/27/grafana-oauth-with-keycloak-and-how-to-validate-a-jwt-token/)
* [How to setup a Keycloak server with external MySQL database on AWS ECS Fargate in clustered mode](https://jbjerksetmyr.medium.com/how-to-setup-a-keycloak-server-with-external-mysql-database-on-aws-ecs-fargate-in-clustered-mode-9775d01cd317)
* [Extending Keycloak: adding API key authentication](http://www.zakariaamine.com/2019-06-14/extending-keycloak)
* [Extending Keycloak: using a custom email sender](http://www.zakariaamine.com/2019-07-14/extending-keycloak2)
* [Integrating Keycloak and OPA with Confluent](https://goraft.tech/2021/03/17/integrating-keycloak-and-opa-with-confluent.html)
* [UMA 2.0 : User Managed Access - how to use it with bash](https://blog.please-open.it/uma/)
* [Setting Up A Keycloak Server For Authenticating To FileMaker](https://soundsessential.medium.com/setting-up-a-keycloak-server-for-authenticating-to-filemaker-introduction-bfe8bba7a8b2)
* [How to Make Keycloak Start Up Faster When There Are a Lot of Offline Sessions](https://medium.com/swlh/how-to-make-keycloak-start-up-faster-when-there-are-a-lot-of-offline-sessions-78ee49a907cb)
* [Using Coder to Develop Keycloak Templates Live (almost)](https://dev.to/m8a-io/m8a-scenario-1-using-coder-to-develop-keycloak-templates-live-almost-26e2)
* [Keycloak Passkeys tutorial](https://keycloak.ch/keycloak-tutorials/tutorial-passkey/)
* [Keycloak as Authorization Server in .NET](https://nikiforovall.github.io/dotnet/keycloak/2022/12/28/keycloak-authorization-server.html)
* [How to use Let's Encrypt certificates with Keycloak](https://kaeruct.github.io/posts/how-to-use-lets-encrypt-certificates-with-keycloak.html)
* [Keycloak Multi-Tenancy and the Pulumi Automation API: Part 1](https://www.zone2.tech/blog/keycloak-multi-tenancy-and-the-pulumi-automation-api-part-1)
* [Instant User Management, SSO, and Secure Pages for ReactJS](https://dev.to/phasetwo/instant-user-management-sso-and-secure-pages-for-reactjs-with-keycloak-4hej)
* [Securing a Next.js Application with Keycloak](https://dev.to/phasetwo/securing-a-nextjs-application-with-keycloak-gm3)
* [Django Web Authentication with Keycloak](https://dev.to/phasetwo/django-web-authentication-with-keycloak-3hl2)
* [Keycloak Workshop for Step Up with MFA Biometrics Authentication (Passkeys) and Passwordless experience with Passkey autofill](https://embesozzi.medium.com/keycloak-workshop-for-step-up-with-mfa-biometrics-authentication-passkeys-b7020ea9ae1b)

## Talks
*  [JDD2015 - Keycloak Open Source Identity and Access Management Solution](https://www.youtube.com/watch?v=TuEkj25lbd0)
*  [2015 Using Tomcat and Keycloak in an iFrame](https://www.youtube.com/watch?v=nF_lw7uIxao)
*  [2016 You've Got Microservices Now Secure Them](https://www.youtube.com/watch?v=SfVhqf-rMQY)
*  [2016 Keycloak: Open Source Single Sign On - Sebastian Rose - AOE conf (german)](https://www.youtube.com/watch?v=wbKw0Bwyne4)
*  [2016 Sécuriser ses applications back et front facilement avec Keycloak (french)](https://www.youtube.com/watch?v=bVidgluUcg0)
*  [2016 Keycloak and Red Hat Mobile Application Platform](https://www.youtube.com/watch?v=4NBgiHM5aOA)
*  [2016 Easily secure your Front and back applications with KeyCloak](https://www.youtube.com/watch?v=RGp4HUKikts)
*  [2017 Easily secure your Spring Boot applications with Keycloak - Part 1](https://developers.redhat.com/video/youtube/vpgRTPFDHAw/)
*  [2017 Easily secure your Spring Boot applications with Keycloak - Part 2](https://developers.redhat.com/video/youtube/O5ePCWON08Y/)
*  [2018 How to secure your Spring Apps with Keycloak by Thomas Darimont @ Spring I/O 2018](https://www.youtube.com/watch?v=haHFoeWUj0w)
*  [2018 DevNation Live | A Deep Dive into Keycloak](https://www.youtube.com/watch?v=ZxpY_zZ52kU)
*  [2018 IDM Europe: WSO2 Identity Server vs. Keycloak (Dmitry Kann)](https://www.youtube.com/watch?v=hnjBiGsEDoU)
*  [2018 JPrime|Building an effective identity and access management architecture with Keycloak (Sebastien Blanc)](https://www.youtube.com/watch?v=bMqcGkCvUVQ)
*  [2018 WJAX| Sichere Spring-Anwendungen mit Keycloak](https://www.youtube.com/watch?v=6Z490EMcafs)
*  [2019 Spring I/O | Secure your Spring Apps with Keycloak](https://www.youtube.com/watch?v=KrOd5wIkqls)
*  [2019 DevoxxFR | Maitriser sa gestion de l'identité avec Keycloak (L. Benoit, T. Recloux, S. Blanc)](https://www.youtube.com/watch?v=0cziL__0-K8)
*  [2019 DevConf | Fine - Grained Authorization with Keycloak SSO (Marek Posolda)](https://www.youtube.com/watch?v=yosg4St0iUw)
*  [2019 VoxxedDays Minsk | Bilding an effective identity and access management architecture with Keycloak (Sebastien Blanc)](https://www.youtube.com/watch?v=RupQWmYhrLA)
*  [2019 Single-Sign-On Authentifizierung mit dem Keycloak Identity Provider | jambit CoffeeTalk](https://www.youtube.com/watch?v=dnY6ORaFNY8)
*  [2020 Keycloak Team | Keycloak Pitch](https://www.youtube.com/watch?v=GZTN_VXjoQw)
*  [2020 Keycloak Team | Keycloak Overview](https://www.youtube.com/watch?v=duawSV69LDI)
*  [2020 Please-open.it : oauth2 dans le monde des ops (french)](https://www.youtube.com/watch?v=S-9X50QajmY)
*  [2022 Secure digital transformation via keycloak's FAPI - DevConf.cz Mini | June 2022](https://www.youtube.com/watch?v=Ao15PH2BAw0)

## Presentations
*  [Keycloak 101](https://stevenolen.github.io/kc101-talk/#1)

## Video Playlists
*  [Keycloak Identity and Access Management by Łukasz Budnik](https://www.youtube.com/playlist?list=PLPZal7ksxNs0mgScrJxrggEayV-TPZ9sA)
*  [Keycloak by Niko Köbler](https://www.youtube.com/playlist?list=PLNn3plN7ZiaowUvKzKiJjYfWpp86u98iY)
*  [Keycloak Playlist by hexaDefence](https://youtu.be/35bflT_zxXA)
*  [Keycloak Tutorial Series by CodeLens](https://www.youtube.com/watch?v=Lr9WeIMtFow&list=PLeGNmkzI56BTjRxNGxUhh4k30FD_gy0pC)
*  [KeycloakDevDay 2024 by dasniko](https://www.youtube.com/watch?v=lQH-yNrF_As&list=PLNn3plN7ZiaqXjiDSB1KDaF3bCDuQmDgw)

## Clients
*  [Official Keycloak Node.js Admin Client](https://github.com/keycloak/keycloak-admin-client/) ("Extremely Experimental")
*  [Keycloak Node.js TypeScript Admin Client by Canner](https://github.com/Canner/keycloak-admin/)
*  [Keycloak Go Client by Cloudtrust](https://github.com/cloudtrust/keycloak-client)
*  [Keycloak Nest.js Admin Client by Relevant Fruit](https://github.com/relevantfruit/nestjs-keycloak-admin)
*  [Keycloak Mock Library](https://github.com/TNG/keycloak-mock)
*  [.NET / C# Keycloak.RestApiClient](https://github.com/fschick/Keycloak.RestApiClient)

## Community Extensions
*  [Keycloak Extensions List](https://www.keycloak.org/extensions.html)
*  [Keycloak Benchmark Project](https://github.com/keycloak/keycloak-benchmark)
*  [Keycloak: Link IdP Login with User Provider](https://github.com/ohioit/keycloak-link-idp-with-user)
*  [Client Owner Manager: Control who can edit a client](https://github.com/cyclone-project/cyclone-client-registration)
*  [Keyloak Proxy written in Go](https://github.com/gambol99/keycloak-proxy)
*  [Script based ProtocolMapper extension for SAML](https://github.com/cloudtrust/keycloak-client-mappers)
*  [Realm export REST resource by Cloudtrust](https://github.com/cloudtrust/keycloak-export)
*  [Keycloak JDBC Ping Setup by moremagic](https://github.com/moremagic/keycloak-jdbc-ping)
*  [SMS 2 Factor Authentication for Keycloak via AWS SNS](https://github.com/nickpack/keycloak-sms-authenticator-sns)
*  [SMS 2 Factor Authentiation for Keycloak via SMS by Alliander](https://github.com/Alliander/keycloak-sms-authenticator)
*  [Identity Provider for vk.com](https://github.com/mrk08/keycloak-vk)
*  [CAS Protocol Support](https://github.com/Doccrazy/keycloak-protocol-cas)
*  [WS-FED Support](https://github.com/cloudtrust/keycloak-wsfed)
*  [Keycloak Discord Support](https://github.com/wadahiro/keycloak-discord)
*  [Keycloak Login with User Attribute](https://github.com/cnieg/keycloak-login-attribute)
*  [zonaut/keycloak-extensions](https://github.com/zonaut/keycloak-extensions)
*  [leroyguillaume/keycloak-bcrypt](https://github.com/leroyguillaume/keycloak-bcrypt)
*  [SPI Authenticator in Nodejs](https://www.npmjs.com/package/keycloak-rest-authenticator)
*  [Have I Been Pwned? Keycloak Password Policy](https://github.com/alexashley/keycloak-password-policy-have-i-been-pwned)
*  [Keycloak Eventlistener for Google Cloud Pub Sub](https://github.com/acesso-io/keycloak-event-listener-gcpubsub)
*  [Enforcing Password policy based on attributes of User Groups](https://github.com/sayedcsekuet/keycloak-user-group-based-password-policy)
*  [Verify Email with Link or Code by hokumski](https://github.com/hokumski/keycloak-verifyemailwithcode)
*  [Role-based Docker registry authentication](https://github.com/lifs-tools/keycloak-docker-role-mapper)
*  [SCIM for keycloak](https://github.com/Captain-P-Goldfish/scim-for-keycloak)
*  [Keycloak Kafka Module](https://github.com/SnuK87/keycloak-kafka)
*  [Useful Keycloak EventListenerProvider implementations and utilities](https://github.com/p2-inc/keycloak-events)
*  [Keycloak: Home IdP Discovery extension](https://github.com/sventorben/keycloak-home-idp-discovery)
*  [Keycloak Metrics SPI](https://github.com/aerogear/keycloak-metrics-spi)
*  [Organizations for Keycloak by p2-inc](https://github.com/p2-inc/keycloak-orgs)
*  [Flexible IdP mapper for OIDC and SAML providers](https://github.com/LucaFilipozzi/keycloak-regex-mapper)
*  [2FA with Code sent via Email](https://github.com/mesutpiskin/keycloak-2fa-email-authenticator)
*  [Admin Portal for User and Organization management by p2-inc](https://github.com/p2-inc/phasetwo-admin-portal)
*  [MagicLink Authenticator by p2-inc](https://github.com/p2-inc/keycloak-magic-link)
*  [Keycloak Metrics based on Micrometer](https://github.com/kokuwaio/keycloak-event-metrics)
*  [softwarefactory-project/keycloak-filter-provider-users](https://github.com/softwarefactory-project/keycloak-filter-provider-users)
*  [rciam/keycloak-group-management](https://github.com/rciam/keycloak-group-management)
*  [embesozzi/keycloak-webauthn-conditional-mediation WebAuthn Support for Passkeys](https://github.com/embesozzi/keycloak-webauthn-conditional-mediation)
*  [Email Notifications when login from a new IP and Login History](https://github.com/eliskachylikova/keycloak-extensions)
*  [Keycloak Authenticator for Duo's Universal Prompt](https://github.com/instipod/DuoUniversalKeycloakAuthenticator)
*  [Keycloak extension for creating multi-tenant IAM for B2B SaaS applications](https://github.com/anarsultanov/keycloak-multi-tenancy)

## Integrations
*  [Keycloak HTTP/MQTT/CoAP IoT Brokers Adapter](https://github.com/authbroker/authbroker)
*  [Official Keycloak Node.js Connect Adapter](https://github.com/keycloak/keycloak-nodejs-connect)
*  [Keycloak support for Aurelia](https://github.com/waynepennington/aurelia-keycloak)
*  [Keycloak OAuth2 Auth for PHP](https://github.com/stevenmaguire/oauth2-keycloak)
*  [Jenkins Keycloak Authentication Plugin](https://github.com/jenkinsci/keycloak-plugin)
*  [Meteor Keycloak Accounts](https://github.com/mxab/meteor-keycloak)
*  [HapiJS Keycloak Auth](https://github.com/felixheck/hapi-auth-keycloak)
*  [zmartzone mod_auth_openidc for Apache 2.x](https://github.com/zmartzone/mod_auth_openidc)
*  [Duo Security MFA Authentication for Keycloak](https://github.com/mulesoft-labs/keycloak-duo-spi)
*  [Extension Keycloak facilitant l'utilisation de FranceConnect](https://github.com/InseeFr/Keycloak-FranceConnect)
*  [Ambassador Keycloak Support](https://www.getambassador.io/reference/idp-support/keycloak/)
*  [Keycloak Python Client](https://github.com/keycloak-client/keycloak-client)
*  [Keycloak Terraform Provider](https://github.com/mrparkers/terraform-provider-keycloak)
*  [Keycloak ADFS OpenID Connect](https://www.michaelboeynaems.com/keycloak-ADFS-OIDC.html)
*  [React/NextJS Keycloak Bindings](https://github.com/panz3r/react-keycloak)
*  [NextJS + tailwind + keycloak integration](https://github.com/santiblanko/keycloak-nextjs-auth)
*  [Keycloak Open-Shift integration](https://github.com/keycloak/openshift-integration)
*  [Keycloak, Kong and Konga setup scripts (local development)](https://github.com/JaouherK/Kong-konga-Keycloak)
*  [SSO for Keycloak and Nextcloud with SAML](https://stackoverflow.com/questions/48400812/sso-with-saml-keycloak-and-nextcloud)
*  [Keycloak Connect GraphQL Adapter for Node.js](https://github.com/aerogear/keycloak-connect-graphql)
*  [python-keycloak](https://github.com/marcospereirampj/python-keycloak)
*  [Keycloak and PrivacyId3a docker-compose (local development)](https://github.com/JaouherK/keycloak-privacyIdea)
*  [Nerzal/gocloak Golang Keycloak API Package](https://github.com/Nerzal/gocloak)
*  [Apple Social Identity Provider for Keycloak](https://github.com/BenjaminFavre/keycloak-apple-social-identity-provider)
*  [Micrometer Keycloak extension](https://github.com/micrometer-metrics/micrometer-keycloak)
*  [Keycloak Provider for Laravel's Socialite Plugin](https://socialiteproviders.com/Keycloak/)
*  [Vault Keycloak Plugin](https://github.com/Serviceware/vault-plugin-secrets-keycloak)
*  [mantelo (Python Admin Client)](https://github.com/derlin/mantelo)

## Quick demo Videos
* [Keycloak with istio envoy jwt-auth proxy](https://www.youtube.com/watch?v=wscX7JMfuBI)

## Themes
*  [Community Keycloak Ionic Theme](https://github.com/lfryc/keycloak-ionic-theme)
*  [A Keycloak theme based on the AdminLTE UI library](https://github.com/MAXIMUS-DeltaWare/adminlte-keycloak-theme)
*  [GOV.UK Theme](https://github.com/UKHomeOffice/keycloak-theme-govuk)
*  [Carbon Design](https://github.com/httpsOmkar/carbon-keycloak-theme)
*  [Modern](https://keycloakthemes.com/themes/modern)
*  [Adminlte](https://git.uptic.nl/uptic-public-projects/uptic-keyclock-theme-adminlte)
*  [keycloakify: Create Keycloak themes using React](https://github.com/InseeFrLab/keycloakify)
*  [Keywind: Component-based theme built with Tailwind CSS](https://github.com/lukin/keywind)
*  [TailwindUI theme](https://github.com/santiblanko/tailwind-keycloak-theme)
*  [Keycloak login theme template](https://github.com/p2-inc/keycloak-theme-template)
*  [Extension for runtime loading of CSS themes](https://github.com/p2-inc/keycloak-themes)
*  [3 CSS-only Keycloak theme examples](https://github.com/p2-inc/keycloak-themes/tree/main/examples)

## Docker
*  [Official Keycloak Docker Images](https://github.com/jboss-dockerfiles/keycloak)
*  [Keycloak Examples as Docker Image](https://hub.docker.com/r/jboss/keycloak-examples)
*  [Keycloak Maven SDK for managing the entire lifecycle of your extensions with Docker](https://github.com/OpenPj/keycloak-docker-quickstart)
*  [Keycloak with CRDB Support](https://quay.io/repository/phasetwo/keycloak-crdb) ([CockroachDB](https://www.cockroachlabs.com/))

## Kubernetes
*  [Deprecated Keycloak Helm Chart](https://github.com/codecentric/helm-charts/tree/master/charts/keycloak)
*  [codecentric Keycloak Helm Chart](https://github.com/codecentric/helm-charts/tree/master/charts/keycloak)
*  [Import / Export Keycloak Config](https://gist.github.com/unguiculus/19618ef57b1863145262191944565c9d)
*  [keycloak-operator](https://github.com/keycloak/keycloak-operator)

## Tools
*  [keycloakmigration: Manage your Keycloak configuration with code](https://github.com/klg71/keycloakmigration)
*  [tool to autogenerate an OpenAPI Specification for Keycloak's Admin API](https://github.com/ccouzens/keycloak-openapi)
*  [oidc-bash-client](https://github.com/please-openit/oidc-bash-client)
*  [louketo-proxy (FKA Gatekeeper)](https://github.com/louketo/louketo-proxy)
*  [keycloak-config-cli: Configuration as Code for Keycloak](https://github.com/adorsys/keycloak-config-cli)
*  [Keycloak Pulumi](https://github.com/pulumi/pulumi-keycloak)
*  [Keycloak on AWS](https://github.com/aws-samples/keycloak-on-aws)
*  [aws-cdk construct library that allows you to create KeyCloak on AWS in TypeScript or Python](https://github.com/aws-samples/cdk-keycloak)
*  [keycloak-scanner Python CLI](https://github.com/NeuronAddict/keycloak-scanner)
*  [Keycloak RestAPI Postman Collection](https://www.postman.com/mverma99/workspace/my-workspace/collection/25610427-e8685d30-4671-45fe-812e-ca10dba1df28)

## Deployment Examples
* [Keycloak deployment with CDK on AWS with Fargate](https://github.com/aws-samples/cdk-keycloak)

## Example Projects
*  [Examples from Keycloak Book: Keycloak - Identity and Access Management for Modern Applications](https://github.com/PacktPublishing/Keycloak-Identity-and-Access-Management-for-Modern-Applications)
*  [Official Examples](https://github.com/keycloak/keycloak/tree/master/examples)
*  [Keycloak Quickstarts](https://github.com/keycloak/keycloak-quickstarts)
*  [Drupal 7.0 with Keycloak](https://gist.github.com/thomasdarimont/17fa146c4fb5440d7fc2ee6322ec392d)
*  [Securing Realm Resources With Custom Roles](https://github.com/dteleguin/custom-admin-roles)
*  [BeerCloak: a comprehensive KeyCloak extension example](https://github.com/dteleguin/beercloak)
*  [KeyCloak Extensions: Securing Realm Resources With Custom Roles](https://github.com/dteleguin/custom-admin-roles)
*  [Red Hat Single Sign-On Labs](https://github.com/RedHatWorkshops/red-hat-sso)
*  [Spring Boot Keycloak Tutorial](https://github.com/sebastienblanc/spring-boot-keycloak-tutorial)
*  [Custom Keycloak Docker Image of Computer Science House of RIT](https://github.com/ComputerScienceHouse/keycloak-docker)
*  [Example of custom password hash SPI for Keycloak](https://github.com/pavelbogomolenko/keycloak-custom-password-hash)
*  [Example for a custom http-client-provider with Proxy support](https://github.com/xiaoyvr/custom-http-client-provider)
*  [Monitor your keycloak with prometheus](https://github.com/larscheid-schmitzhermes/keycloak-monitoring-prometheus)
*  [Custom User Storage Provider .ear with jboss-cli setup](https://github.com/thomasdarimont/keycloak-user-storage-provider-demo)
*  [Keycloak - Experimental extensions by Stian Thorgersen/Keycloak](https://github.com/stianst/keycloak-experimental)
*  [Securing Spring Boot Admin & Actuator Endpoints with Keycloak](https://github.com/thomasdarimont/spring-boot-admin-keycloak-example)
*  [A Keycloak Mobile Implementation using Angular v4 and Ionic v3](https://github.com/tomjackman/keyonic-v2)
*  [Example for Securing Apps with Keycloak on Kubernetes](https://github.com/stianst/demo-kubernetes)
*  [Example for Securing AspDotNet Core Apps with Keycloak](https://github.com/thomasdarimont/kc-dnc-demo)
*  [Example for passing custom URL parameters to a Keycloak theme for dynamic branding](https://github.com/dteleguin/keycloak-dynamic-branding)
*  [Angular Webapp secured with Keycloak](https://github.com/CodepediaOrg/bookmarks.dev)
*  [Keycloak Theme Development Kit](https://github.com/anthonny/kit-keycloak-theme)
*  [Keycloak Clustering examples](https://github.com/ivangfr/keycloak-clustered)
*  [Keycloak Last Login Date Event Listener](https://github.com/ThoreKr/keycloak-last-login-event-listener)
*  [Keycloak Project Example (Customizations, Extensions, Configuration)](https://github.com/thomasdarimont/keycloak-project-example)
*  [Example of adding API Key authentication to Keycloak](https://github.com/zak905/keycloak-api-key-demo)
*  [Example for using Keycloak Authorization with ASP.NET Core](https://github.com/NikiforovAll/keycloak-authorization-services-dotnet)
*  [FAPI demo from DevConf.cz Mini: Secure digital transformation via keycloak's FAPI](https://github.com/mposolda/fapi-demo/tree/main)
*  [Keycloak enviornment with WebAuthn Support for Stepup Auth with MFA Biometrics and Passkeys (by embesozzi)](https://github.com/embesozzi/keycloak-workshop-stepup-mfa-biometrics)
*  [How to: Keycloak - ASP.NET Core - Angular](https://github.com/fschick/Keycloak.ASPNet.Angular)
*  [Verifiable Credential Authentication with OpenID Connect (VC-AuthN OIDC)](https://github.com/bcgov/vc-authn-oidc)
*  [FIDO2 with Keycloak for 1FA and 2FA christian-2/oidc-passkey](https://github.com/christian-2/oidc-passkey)
*  [A simple Django app to use Keycloak over OIDC by Amsterdam/keycloak_oidc](https://github.com/Amsterdam/keycloak_oidc)

## Benchmarks
*  [Gatling based Benchmark by @rvansa](https://github.com/rvansa/keycloak-benchmark)

## Help
* [Keycloak on Stackoverflow](https://stackoverflow.com/questions/tagged/keycloak)

## Commercial Offerings
*  [Red Hat build of Keycloak](https://access.redhat.com/products/red-hat-build-of-keycloak)
*  [Red Hat Single Sign-On](https://access.redhat.com/products/red-hat-single-sign-on)
*  [INTEGSOFT UNIFIED USER CREDENTIALS WITH KEYCLOAK SSO](https://www.integsoft.cz/en/sso.html#what-is-sso)
*  [JIRA SSO Plugin by codecentric](https://marketplace.atlassian.com/plugins/de.codecentric.atlassian.oidc.jira-oidc-plugin/server/overview)
*  [Keycloak Competence Center by Inventage AG](https://keycloak.ch/)
*  [Keycloak as a Service](https://www.cloud-iam.com)
*  [Bare.Id - GDPR compliant Keycloak as a Service](https://bare.id/)
*  Phase Two [Keycloak hosting](https://phasetwo.io/) and on-prem [Keycloak support](https://phasetwo.io/product/onprem)
*  [Skycloak](https://skycloak.io/)

## Miscellaneous
*  [Find sites using Keycloak with google](https://www.google.de/search?q=inurl%3Aauth+inurl%3Arealms+inurl%3Aprotocol&oq=inurl%3A&client=ubuntu&sourceid=chrome&ie=UTF-8)
*  [Keycloak Dev Bookmarks](http://bookmarks.dev/search?q=keycloak) - Use the tag [keycloak](https://www.bookmarks.dev/tagged/keycloak)
*  [Use fail2ban to block brute-force attacks to keycloak server](https://gist.github.com/drmalex07/3eba8b98d0ac4a1e821e8e721b3e1816)
*  [Pentest-Report Keycloak 8.0 Audit & Pentest 11.2019 by Cure53](https://cure53.de/pentest-report_keycloak.pdf)
*  [Keycloak - CNCF Security SIG - Self Assesment](https://docs.google.com/document/d/14IIGliP3BWjdS-0wfOk3l_1AU8kyoSiLUzpPImsz4R0/edit#)

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Thomas Darimont](https://github.com/thomasdarimont) has waived all copyright and related or neighboring rights to this work.
