# What is the Authenticator Registry?

## 1. Next-Generation identity federation

As individual universities and research institutes began using integrated authentication infrastructures for institution-wide services, the demand for more advanced and secure usage emerged. In other words, there is an increasing need to establish an environment where services, such as supercomputers and research infrastructures - whose provision has been discouraged due to security concerns, or whose complex authentication was provided individually - can be accessed through IdP authentication by enabling IdPs to offer robust authentication.

In response to this, GakuNin began researching and developing the n next-Generation identity federation infrastructure. We established the Working Group for Next-Generation Identity Federation and are working toward its realization.

## 2. Authenticator Assurance Level

As part of this initiative, a policy was established by the Working Group for Next-Generation Identity Federation to operate the GakuNin AAL (Authenticator Assurance Level) standards, which define multi-factor authentication as a stronger authentication method. This policy is implemented with IdPs as the control target. The aim is to implement AAL2, a stronger authentication standard, for services that require a higher level of security.

The AAL2 standards are defined in accordance with NIST SP800-63 and Kantara KIAF1440.

## 3. What is the Authenticator Registry?

In the GakuNin AAL2 standards, it is described that GakuNin should establish and provide an Authenticator Registry for its operation. The Authenticator Registry is a registry that stores information related to GakuNin AAL2-compliant authenticators, with the purpose of providing information to GakuNin-participating IdPs.

## 4. Benefit of the Authenticator Registry 1 (Reduced Workload)

To accredit and operate GakuNin AAL2, it is necessary to evaluate the large number of authenticators available in the market. However, it is not practical for each GakuNin-participating institution to individually evaluate AAL2 compliance for each authenticator, given the workload and costs involved.

For example, when conducting an evaluation, various factors need to be considered, such as the following:

1.  What type does this authenticator fall under?
2.  Does this authenticator meet the requirements of the GakuNin AAL2 standards?
3.  Is this authenticator single-factor or multi-factor on its own?
4.  What operational issues does this authenticator present?
5.  What security risks does this authenticator pose?

Naturally, this requires a significant amount of work, and in some cases, it may be necessary to hire individuals with specialized knowledge.

We believe that, in terms of reducing workloads and cost-effectiveness, it is rational for GakuNin to evaluate the performance of authenticators, determine whether they meet the AAL2 standards for authentication, and provide an Authenticator Registry that shares and publishes the results.

## 5. Benefit of the Authenticator Registry 2 (As a Source of Information)

The Authenticator Registry also provides various information related to authenticators.

For example, by providing information about the types and mechanisms of authenticators, GakuNin-participating institutions can use this information to select authenticators that best suit their needs. Additionally, it helps institutions ensure proper operation by understanding security risks and taking appropriate measures. Furthermore, by providing information on how to configure and use the authenticators, GakuNin-participating institutions can streamline implementation and improve operational efficiency.

## 6. Conclusion

Through the Authenticator Registry, we will provide essential information for introducing and operating the AAL2 standards within GakuNin. Additionally, we plan to regularly perform maintenance to ensure that the registry remains a reliable and up-to-date information source.
