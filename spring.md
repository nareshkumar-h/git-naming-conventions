# Project Name: spring-boot
| Author | Commit Message |
|--|--|
|Phillip Webb|Merge branch '1.5.x'|
|Phillip Webb|Backport use docker-java 3.0.x for launch tests|
|Stephane Nicoll|Improve documentation for WebTestClient|
|Andy Wilkinson|Correct test expectations following changes to application context ID|
|Andy Wilkinson|Make ContextIdApplicationContextInitializer produce unique IDs|
|Johnny Lim|Fix imports order for Checkstyle|
|Madhura Bhave|Provide EndpointRequest for WebFlux-based Security|
|Madhura Bhave|Fix imports|
|Madhura Bhave|Fix javadoc|
|Madhura Bhave|Update copyright year of changed files|
|Madhura Bhave|Fix package tangle in cloudfoundry configuration|
|Phillip Webb|Update copyright year of changed files|
|Phillip Webb|Polish|
|Phillip Webb|Extract RestDocsProperties|
|Andy Wilkinson|Use docker-java 3.0.x for launch script integration tests|
|Stephane Nicoll|Add missing artifact required for the Javadoc task|
|Stephane Nicoll|Merge branch '1.5.x'|
|Stephane Nicoll|Fix detection of dot-based resource bundle basenames|
|Andy Wilkinson|Polish "Add auto-configuration for using REST Docs with WebTestClient"|
|Roman Zaynetdinov|Add auto-configuration for using REST Docs with WebTestClient|
|Andy Wilkinson|Introduce WebTestClientBuilderCustomizer callback|
|Andy Wilkinson|Merge branch '1.5.x'|
|Andy Wilkinson|Remove dependency management for selenium-opera-driver|
|Andy Wilkinson|Upgrade to Javax Cache 1.1.0|
|Stephane Nicoll|Polish WebFlux.fn documentation|
|Johnny Lim|Use instance equality for Class|
|Johnny Lim|Polish|
|Phillip Webb|Polish GSON customization support|
|ioann|Allow GSON customization via properties or beans|
|Phillip Webb|Create DynamicRegistrationBean|
|Phillip Webb|Fix NPE in test containers|
|Phillip Webb|Revert "Build against Spring Security 5.0.1 SNAPSHOT"|
|Phillip Webb|Further refine test containers|
|Phillip Webb|Further refine test containers|
|Phillip Webb|Build against Spring Security 5.0.1 SNAPSHOT|
|Phillip Webb|Make WebMvcMetricsFilter lazy|
|Phillip Webb|Refine BackgroundPreinitializer|
|Phillip Webb|Propagate Map conversion failures|
|Phillip Webb|Polish|
|Phillip Webb|Polish InvalidConfigurationPropertyValueException|
|Phillip Webb|Polish ConfigurationPropertiesBinder|
|Phillip Webb|Update copyright header used in Eclipse template|
|Madhura Bhave|Use TestContainers util from spring-boot-test-support|
|Andy Wilkinson|Refine test containers|


# Project Name: spring-framework
| Author | Commit Message |
|--|--|
|Rossen Stoyanchev|ResourceUrlProvider handles sanitizes double slashes|
|Rossen Stoyanchev|Expand docs on WebFlux.fn + @EnableWebFlux|
|sdeleuze|Fix Kotlin bean w/ default + secondary ctors handling|
|Arjen Poutsma|Javadoc|
|Arjen Poutsma|Reverted signature change on fromMultipartData|
|Rossen Stoyanchev|Uncomment test after Reactor Netty fix|
|Arjen Poutsma|Use write aggregator from DataBufferUtils|
|Arjen Poutsma|Introduce write aggregator to DataBufferUtils|
|Arjen Poutsma|Remove use of CompositeByteBuf in NettyDataBuffer|
|Rossen Stoyanchev|Fix init issues in AbstractReactiveWebInitializer|
|Rossen Stoyanchev|Polish|
|Jeff Nelson|Extract protected method in AbstractRequestLoggingFilter|
|Juergen Hoeller|Polishing|
|Juergen Hoeller|SqlParameterSource interface exposes parameter names|
|Juergen Hoeller|Support for PostgreSQL array syntax|
|Masahiro Ide|ResourceBundleMessageSource uses ConcurrentHashMaps instead of synchronization|
|Toshiaki Maki|Fix source code in doc|
|sdeleuze|Polishing|
|sdeleuze|Refine forwarded protocol support|
|Rossen Stoyanchev|Improve error message|
|Rossen Stoyanchev|Polish|
|Aleksey Voronenkov|Overloaded methods in InterceptorRegistration|
|Juergen Hoeller|Check BeanInfoFactory for interface introspection as well|
|Rossen Stoyanchev|Links from @RequestMapping to reference docs|
|Juergen Hoeller|Upgrade to HtmlUnit 2.29 and Selenium 3.8.1|
|Juergen Hoeller|Warning instead of error for non-present type filter class|
|Stephane Nicoll|Fix SpEL syntax|
|Juergen Hoeller|CachingConnectionFactory does not cache producer for temporary queue/topic|
|Juergen Hoeller|Build against OpenPDF 1.0.5 instead of outdated iText 2.1.7|
|Skelotron|SPR-16316 — fix transaction timeout value overflow|
|Juergen Hoeller|Polishing|
|Juergen Hoeller|Direct reference to JPA 2.1 SynchronizationType enum|
|Juergen Hoeller|LoadTimeWeaver detection differentiates between WebSphere and Liberty|
|Juergen Hoeller|FunctionReference's method field is volatile|
|Juergen Hoeller|Relaxed BeanFactory assertion in resolveInterceptorNames|
|Juergen Hoeller|Properly handle null bean instance in getLifecycleBeans|
|Juergen Hoeller|Properly handle null FactoryBean instance|
|Juergen Hoeller|Consider enum subclasses as simple value types as well|
|Juergen Hoeller|Support for static field access on non-public enums|
|Juergen Hoeller|Avoid extra existence check in SimpleMetadataReaderFactory|
|Juergen Hoeller|Consistently throw FileNotFoundException even for NIO access|
|Rossen Stoyanchev|Access to ApplicationContext via ServerWebExchange|
|Rossen Stoyanchev|Fix regression in BodyInserters with multipart data|
|Rossen Stoyanchev|Document Jackson encoder/decoder behavior|
|Rossen Stoyanchev|Improve HTTP message reading/writing docs|
|Rossen Stoyanchev|Add hasJsonPath/doesNotHaveJsonPath assertion options|
