---
layout: page
title:  "Link Relations"
---



The following 85 Link Relation definitions (82 distinct values) were found in 123 services. Please be advised that the table shown here is maintained and compiled from [Web Concepts](/) sources. The [official Link Relation registry](http://www.iana.org/assignments/link-relations/link-relations.xhtml) is maintained by the [*Internet Assigned Numbers Authority (IANA)*](http://www.iana.org/).

Link Relation | Description | Specification
-------: | :---------- | :---
`about` | "[The "about" link relation can be used to refer to a resource that is the subject or topic of the link's context. Multiple subjects can be indicated through the use of multiple "about" link relations.](http://tools.ietf.org/html/rfc6903#section-2)" | [**RFC 6903**: Additional Link Relation Types](/specs/IETF/RFC/6903)
`alternate` <sub>(2 definitions)</sub> | "[The value "alternate" signifies that the IRI in the value of the href attribute identifies an alternate version of the resource described by the containing element.](http://tools.ietf.org/html/rfc4287#section-4.2.7.2)" | [**RFC 4287**: Atom Syndication Format](/specs/IETF/RFC/4287)
`alternate` <sub>(2 definitions)</sub> | "[Designates substitute versions for the document in which the link occurs. When used together with the lang attribute, it implies a translated version of the document. When used together with the media attribute, it implies a version designed for a different medium (or media).](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`appendix` | "[Refers to a document serving as an appendix in a collection of documents.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`bcc` | "[Refers to a resource that is considered to be part of the private secondary audience of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`bfrom` | "[Refers to a resource that is privately considered to be the originator of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`bookmark` | "[Refers to a bookmark. A bookmark is a link to a key entry point within an extended document. The title attribute may be used, for example, to label the bookmark. Note that several bookmarks may be defined in each document.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`bto` | "[Refers to a resource that is considered to be part of the private primary audience of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`canonical` | "[The target (canonical) IRI MUST identify content that is either duplicative or a superset of the content at the context (referring) IRI.](http://tools.ietf.org/html/rfc6596#section-3)" | [**RFC 6596**: The Canonical Link Relation](/specs/IETF/RFC/6596)
`cc` | "[Refers to a resource that is considered to be  part of the public secondary audience of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`chapter` | "[Refers to a document serving as a chapter in a collection of documents.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`collection` | "[When included in a resource that represents a member of a collection, the 'collection' link relation identifies a target resource that represents a collection of which the context resource is a member.](http://tools.ietf.org/html/rfc6573#section-2.2)" | [**RFC 6573**: The Item and Collection Link Relations](/specs/IETF/RFC/6573)
`contents` | "[Refers to a document serving as a table of contents. Some user agents also support the synonym ToC (from "Table of Contents").](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`copyright` | "[Refers to a copyright statement for the current document.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`create` | "[This indicates a target to use for creating new instances of a schema. This link definition SHOULD be a submission link with a non-safe method (like POST).](http://tools.ietf.org/html/draft-zyp-json-schema#section-6.1.1.2)" | [**Internet Draft zyp-json-schema**: A JSON Media Type for Describing the Structure and Meaning of JSON Documents](/specs/IETF/I-D/zyp-json-schema)
`create-form` | "[When included in a response, the "create-form" link relation indicates a target resource that represents a form that can be used to append a new member to the link context.](http://tools.ietf.org/html/rfc6861#section-3.1)" | [**RFC 6861**: The "create-form" and "edit-form" Link Relations](/specs/IETF/RFC/6861)
`current` | "[A URI that, when dereferenced, returns a feed document containing the most recent entries in the feed.](http://tools.ietf.org/html/rfc5005#section-4)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`derivedfrom` | "[The document linked to was later converted to the document that contains this link relation. For example, an RFC can have a link to the Internet Draft that became the RFC; in that case, the link relation would be "derivedfrom".](https://tools.ietf.org/html/draft-hoffman-xml2rfc-15#section-6.2)" | [**Internet Draft hoffman-xml2rfc**: The 'XML2RFC' version 3 Vocabulary](/specs/IETF/I-D/hoffman-xml2rfc)
`describedby` <sub>(2 definitions)</sub> | "[The relationship A describedby B asserts that resource B provides a description of resource A. There are no constraints on the format or representation of either A or B, neither are there any further constraints on either resource.](http://www.w3.org/TR/ldp/#link-relation-describedby)" | [**W3C TR http://www.w3.org/TR/ldp**: Linked Data Platform 1.0 (LDP)](/specs/W3C/TR/ldp)
`describedby` <sub>(2 definitions)</sub> | "[The relationship A 'describedby' B asserts that resource B provides a description of resource A. There are no constraints on the format or representation of either A or B, neither are there any further constraints on either resource.](http://www.w3.org/TR/powder-dr/#appD)" | [**W3C TR http://www.w3.org/TR/powder-dr**: Protocol for Web Description Resources (POWDER): Description Resources](/specs/W3C/TR/powder-dr)
`describes` | "[The relationship A 'describes' B asserts that resource A provides a description of resource B. There are no constraints on the format or representation of either A or B, neither are there any further constraints on either resource.](http://tools.ietf.org/html/rfc6892#section-2)" | [**RFC 6892**: The 'describes' Link Relation Type](/specs/IETF/RFC/6892)
`disclosure` | "[Whenever the 'disclosure' relation type is used, the resource at the target Internationalized Resource Identifier (IRI) MUST represent a list of patent disclosures made with respect to the material referenced by context IRI.](http://tools.ietf.org/html/rfc6579#section-2)" | [**RFC 6579**: The 'disclosure' Link Relation Type](/specs/IETF/RFC/6579)
`dns-prefetch` | "[The dns-prefetch link relation type is used to indicate an origin that will be used to fetch required resources, and that the user agent SHOULD resolve as early as possible.](www.w3.org/TR/resource-hints/#dns-prefetch)" | [**W3C TR http://www.w3.org/TR/resource-hints**: Resource Hints](/specs/W3C/TR/resource-hints)
`down` | "[An Atom link element with a rel attribute value of "down" may be used to reference a resource where child entries of an entry may be found.](http://tools.ietf.org/html/draft-divilly-atom-hierarchy#section-2.2)" | [**Internet Draft divilly-atom-hierarchy**: Hierarchy Relations for Atom](/specs/IETF/I-D/divilly-atom-hierarchy)
`edit` | "[The value of "edit" specifies that the value of the href attribute is the IRI of an editable Member Entry. When appearing within an atom:entry, the href IRI can be used to retrieve, update, and delete the Resource represented by that Entry. An atom:entry MUST NOT contain more than one "edit" link relation.](http://tools.ietf.org/html/rfc5023#section-11.1)" | [**RFC 5023**: Atom Publishing Protocol (AtomPub)](/specs/IETF/RFC/5023)
`edit-form` | "[When included in a response, the "edit-form" link relation indicates a target resource that represents a form that can be used for updating the context resource.](http://tools.ietf.org/html/rfc6861#section-3.2)" | [**RFC 6861**: The "create-form" and "edit-form" Link Relations](/specs/IETF/RFC/6861)
`edit-media` | "[When appearing within an atom:entry, the value of the href attribute is an IRI that can be used to modify a Media Resource associated with that Entry.](http://tools.ietf.org/html/rfc5023#section-11.2)" | [**RFC 5023**: Atom Publishing Protocol (AtomPub)](/specs/IETF/RFC/5023)
`enclosure` | "[The value "enclosure" signifies that the IRI in the value of the href attribute identifies a related resource that is potentially large in size and might require special handling. For atom:link elements with rel="enclosure", the length attribute SHOULD be provided.](http://tools.ietf.org/html/rfc4287#section-4.2.7.2)" | [**RFC 4287**: Atom Syndication Format](/specs/IETF/RFC/4287)
`first` | "[A URI that refers to the furthest preceding document in a series of documents.](http://tools.ietf.org/html/rfc5005#section-3)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`from` | "[Refers to a resource that is publicly considered to be the originator of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`full` | "[This indicates that the target of the link is the full representation for the instance object. The object that contains this link possibly may not be the full representation.](http://tools.ietf.org/html/draft-zyp-json-schema#section-6.1.1.2)" | [**Internet Draft zyp-json-schema**: A JSON Media Type for Describing the Structure and Meaning of JSON Documents](/specs/IETF/I-D/zyp-json-schema)
`generator` | "[Refers to the resource that generated the context  resource. Typically, this would be used to identify the software application that created the context resource.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`glossary` | "[Refers to a document providing a glossary of terms that pertain to the current document.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`help` | "[Refers to a document offering help (more information, links to other sources information, etc.)](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`home` | "[Identifies a resource that provides a "home" document for the context resource. Home documents often serve as starting points for a certain resource context, such as for Web APIs where the home resource provides access to a number of "entry points" to the Web API.](http://tools.ietf.org/html/draft-wilde-home-xml-04#section-4.3.1)" | [**Internet Draft wilde-home-xml**: Home Documents for HTTP Services: XML Syntax](/specs/IETF/I-D/wilde-home-xml)
`hosts` | "[Refers to a resource hosted by the server indicated by the link context.](http://tools.ietf.org/html/rfc6690#section-7.2)" | [**RFC 6690**: Constrained RESTful Environments (CoRE) Link Format](/specs/IETF/RFC/6690)
`index` | "[Refers to a document providing an index for the current document.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`instances` | "[This indicates the target resource that represents collection of instances of a schema.](http://tools.ietf.org/html/draft-zyp-json-schema#section-6.1.1.2)" | [**Internet Draft zyp-json-schema**: A JSON Media Type for Describing the Structure and Meaning of JSON Documents](/specs/IETF/I-D/zyp-json-schema)
`item` | "[When included in a resource that represents a collection, the 'item' link relation identifies a target resource that represents a member of that collection.](http://tools.ietf.org/html/rfc6573#section-2.1)" | [**RFC 6573**: The Item and Collection Link Relations](/specs/IETF/RFC/6573)
`last` | "[A URI that refers to the furthest following document in a series of documents.](http://tools.ietf.org/html/rfc5005#section-3)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`latest-version` | "[When included on a versioned resource, this link points to a resource containing the latest (e.g., current) version.](http://tools.ietf.org/html/rfc5829#section-3.2)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)
`license` | "[The "license" link relation can be used to associate licenses with a feed or entry. Feeds and entries can be dual-licensed by including multiple "license" link relations specifying different href attribute values. If multiple "license" link relations are specified, each SHOULD contain a title attribute specifying a human-readable label for the license.](http://tools.ietf.org/html/rfc4946#section-2)" | [**RFC 4946**: Atom License Extension](/specs/IETF/RFC/4946)
`link` | "[In the simplest case, a link relation type identifies the semantics of a link. For example, a link with the relation type "copyright" indicates that the resource identified by the target IRI is a statement of the copyright terms applying to the current context IRI. Link relation types can also be used to indicate that the target resource has particular attributes, or exhibits particular behaviours; for example, a "service" link implies that the identified resource is part of a defined protocol (in this case, a service description).](http://tools.ietf.org/html/rfc5988#section-4)" | [**RFC 5988**: Web Linking](/specs/IETF/RFC/5988)
`location` | "[References a URI/IRI that represents a physical or logical location with which the context resource is associated.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`manifest` | "[Imports or links to a manifest.](http://www.w3.org/TR/appmanifest/#linking)" | [**W3C TR http://www.w3.org/TR/appmanifest**: Manifest for Web Application](/specs/W3C/TR/appmanifest)
`memento` | "[A link with a "memento" Relation Type is used to point from a TimeGate or a Memento for an Original Resource, as well as from the Original Resource itself, to a Memento for the Original Resource.](http://tools.ietf.org/html/rfc7089#section-2.2.4)" | [**RFC 7089**: HTTP framework for time-based access to resource states - Memento](/specs/IETF/RFC/7089)
`mentionedby` | "[Refers to a resource that mentions the context resource in some fashion. This, for example, would be used when an article mentions another article, or a social status update mentions a particular user, etc.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`micropub` | "[Allows discovery of a Micropub endpoint which will be used to create posts.](https://www.w3.org/TR/micropub/#endpoint-discovery)" | [**W3C TR http://www.w3.org/TR/micropub**: Micropub](/specs/W3C/TR/micropub)
`next` <sub>(2 definitions)</sub> | "[A URI that refers to the immediately following document in a series of documents.](http://tools.ietf.org/html/rfc5005#section-3)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`next` <sub>(2 definitions)</sub> | "[Refers to the next document in a linear sequence of documents. User agents may choose to preload the "next" document, to reduce the perceived load time.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`next-archive` | "[A URI that refers to the immediately following archive document.](http://tools.ietf.org/html/rfc5005#section-4)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`original` | "[A link with an "original" Relation Type is used to point from a TimeGate or a Memento to its associated Original Resource.](http://tools.ietf.org/html/rfc7089#section-2.2.1)" | [**RFC 7089**: HTTP framework for time-based access to resource states - Memento](/specs/IETF/RFC/7089)
`preconnect` | "[The preconnect link relation type is used to indicate an origin that will be used to fetch required resources. Initiating an early connection, which includes the DNS lookup, TCP handshake, and optional TLS negotiation, allows the user agent to mask the high latency costs of establishing a connection.](http://www.w3.org/TR/resource-hints/#preconnect)" | [**W3C TR http://www.w3.org/TR/resource-hints**: Resource Hints](/specs/W3C/TR/resource-hints)
`predecessor-version` | "[When included on a versioned resource, this link points to a resource containing the predecessor version in the version history.](http://tools.ietf.org/html/rfc5829#section-3.5)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)
`prefetch` | "[The prefetch link relation type is used to declare a resource that might be required by the next navigation, and that the user agent SHOULD fetch, such that the user agent can deliver a faster response once the resource is requested in the future.](http://www.w3.org/TR/resource-hints/#prefetch)" | [**W3C TR http://www.w3.org/TR/resource-hints**: Resource Hints](/specs/W3C/TR/resource-hints)
`preload` | "[The preload keyword may be used with link elements. This keyword creates an external resource link (preload link) that is used to declare a resource and its fetch properties.](http://www.w3.org/TR/preload/#link-type-preload)" | [**W3C TR http://www.w3.org/TR/preload**: Preload](/specs/W3C/TR/preload)
`prerender` | "[The prerender link relation type is used to declare an HTML resource that might be required by the next navigation, and that the user agent SHOULD fetch and execute, such that the user agent can deliver faster response and processing once the resource is requested in the future.](http://www.w3.org/TR/resource-hints/#prerender)" | [**W3C TR http://www.w3.org/TR/resource-hints**: Resource Hints](/specs/W3C/TR/resource-hints)
`prev` | "[Refers to the previous document in an ordered series of documents. Some user agents also support the synonym "Previous".](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`prev-archive` | "[A URI that refers to the immediately preceding archive document.](http://tools.ietf.org/html/rfc5005#section-4)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`preview` | "[The "preview" link relation can be used to refer to a resource that serves as a preview of the link's context, likely with reduced quality or limited content. For instance, the preview link might reference a screen capture of a video, a brief snippet of audio from a song, or a thumbnail representation of an image.](http://tools.ietf.org/html/rfc6903#section-3)" | [**RFC 6903**: Additional Link Relation Types](/specs/IETF/RFC/6903)
`previous` | "[A URI that refers to the immediately preceding document in a series of documents.](http://tools.ietf.org/html/rfc5005#section-3)" | [**RFC 5005**: Feed Paging and Archiving](/specs/IETF/RFC/5005)
`privacy-policy` | "[The "privacy-policy" link relation can be used to refer to a resource describing the privacy policy associated with the link's context. The privacy policy can be any resource that discloses what personal information about the user is collected and how that personal information is stored, used, managed, and disclosed to other parties.](http://tools.ietf.org/html/rfc6903#section-4)" | [**RFC 6903**: Additional Link Relation Types](/specs/IETF/RFC/6903)
`provider` | "[Refers to the resource that provided the context resource. Typically, this would be used to identify the entity publishing the resource.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`related` | "[The value "related" signifies that the IRI in the value of the href attribute identifies a resource related to the resource described by the containing element. For example, the feed for a site that discusses the performance of the search engine at "http://search.example.com" might contain, as a child of atom:feed: <link rel="related" href="http://search.example.com/"/> An identical link might appear as a child of any atom:entry whose content contains a discussion of that same search engine.](http://tools.ietf.org/html/rfc4287#section-4.2.7.2)" | [**RFC 4287**: Atom Syndication Format](/specs/IETF/RFC/4287)
`root` | "[This relation indicates that the target of the link SHOULD be treated as the root or the body of the representation for the purposes of user agent interaction or fragment resolution. All other properties of the instance objects can be regarded as meta-data descriptions for the data.](http://tools.ietf.org/html/draft-zyp-json-schema#section-6.1.1.2)" | [**Internet Draft zyp-json-schema**: A JSON Media Type for Describing the Structure and Meaning of JSON Documents](/specs/IETF/I-D/zyp-json-schema)
`section` | "[Refers to a document serving as a section in a collection of documents.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`self` | "[The value "self" signifies that the IRI in the value of the href attribute identifies a resource equivalent to the containing element.](http://tools.ietf.org/html/rfc4287#section-4.2.7.2)" | [**RFC 4287**: Atom Syndication Format](/specs/IETF/RFC/4287)
`service-desc` | "[Used to represent the fact that a resource is part of a bigger set of resources that are described at a specific URI. The target resource is expected to provide a service description that is intended for machine consumption. Very often, it is provided in a format that is consumed by tools, code libraries, or similar components.](http://tools.ietf.org/html/draft-wilde-service-link-rel#section-4.2)" | [**Internet Draft wilde-link-desc**: Link Relation Types for Web Services](/specs/IETF/I-D/wilde-link-desc)
`service-doc` | "[Used to represent the fact that a resource is part of a bigger set of resources that are documented at a specific URI. The target resource is expected to provide documentation that is intended for human consumption.](http://tools.ietf.org/html/draft-wilde-service-link-rel#section-4.1)" | [**Internet Draft wilde-link-desc**: Link Relation Types for Web Services](/specs/IETF/I-D/wilde-link-desc)
`source` | "[Refers to the original source of information contained by the context resource.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`start` | "[Refers to the first document in a collection of documents. This link type tells search engines which document is considered by the author to be the starting point of the collection.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`stylesheet` | "[Refers to an external style sheet. See the section on external style sheets for details. This is used together with the link type "Alternate" for user-selectable alternate style sheets.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`subsection` | "[Refers to a document serving as a subsection in a collection of documents.](http://www.w3.org/TR/html4/types.html#type-links)" | [**W3C TR http://www.w3.org/TR/html4**: Hypertext Markup Language (HTML)](/specs/W3C/TR/html4)
`successor-version` | "[When included on a versioned resource, this link points to a resource containing the successor version in the version history.](http://tools.ietf.org/html/rfc5829#section-3.6)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)
`terms-of-service` | "[The "terms-of-service" link relation can be used to refer to a resource describing the terms of service associated with the link's context. The terms of service can be any resource that describes the rules to which a consumer of the service must agree to follow when using the service provided by the link's context.](http://tools.ietf.org/html/rfc6903#section-5)" | [**RFC 6903**: Additional Link Relation Types](/specs/IETF/RFC/6903)
`timegate` | "[A link with a "timegate" Relation Type is used to point from the Original Resource, as well as from a Memento associated with the Original Resource, to a TimeGate for the Original Resource.](http://tools.ietf.org/html/rfc7089#section-2.2.2)" | [**RFC 7089**: HTTP framework for time-based access to resource states - Memento](/specs/IETF/RFC/7089)
`timemap` | "[A link with a "timemap" Relation Type is used to point from a TimeGate or a Memento associated with an Original Resource, as well as from the Original Resource itself, to a TimeMap for the Original Resource.](http://tools.ietf.org/html/rfc7089#section-2.2.3)" | [**RFC 7089**: HTTP framework for time-based access to resource states - Memento](/specs/IETF/RFC/7089)
`to` | "[Refers to a resource that is considered to be part of the public primary audience of the link's context.](http://tools.ietf.org/html/draft-snell-more-link-relations#section-3)" | [**Internet Draft snell-more-link-relations**: Additional Link Relations and the urn:social Namespace](/specs/IETF/I-D/snell-more-link-relations)
`type` | "[The "type" link relation can be used to indicate that the context resource is an instance of the resource identified by the target Internationalized Resource Identifier (IRI).](http://tools.ietf.org/html/rfc6903#section-6)" | [**RFC 6903**: Additional Link Relation Types](/specs/IETF/RFC/6903)
`up` | "[An Atom link element with a rel attribute value of "up" may be used to reference a resource where parent entries of an entry or a feed may be found.](http://tools.ietf.org/html/draft-divilly-atom-hierarchy#section-2.3)" | [**Internet Draft divilly-atom-hierarchy**: Hierarchy Relations for Atom](/specs/IETF/I-D/divilly-atom-hierarchy)
`version-history` | "[When included on a versioned resource, this link points to a resource containing the version history for this resource.](http://tools.ietf.org/html/rfc5829#section-3.1)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)
`via` | "[The value "via" signifies that the IRI in the value of the href attribute identifies a resource that is the source of the information provided in the containing element.](http://tools.ietf.org/html/rfc4287#section-4.2.7.2)" | [**RFC 4287**: Atom Syndication Format](/specs/IETF/RFC/4287)
`webmention` | "[Identifies a target URI that supports the Webmention protocol. This allows clients that mention a resource in some form of publishing process to contact that endpoint and inform it that this resource has been mentioned.](https://www.w3.org/TR/webmention/#sender-discovers-receiver-webmention-endpoint)" | [**W3C TR http://www.w3.org/TR/webmention**: Webmention](/specs/W3C/TR/webmention)
`working-copy` | "[When included on a versioned resource, this link points to a working copy for this resource.](http://tools.ietf.org/html/rfc5829#section-3.3)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)
`working-copy-of` | "[When included on a working copy, this link points to the versioned resource from which this working copy was obtained.](http://tools.ietf.org/html/rfc5829#section-3.4)" | [**RFC 5829**: Link Relation Types for Simple Version Navigation between Web Resources](/specs/IETF/RFC/5829)