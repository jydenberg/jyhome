{
    "title":"HSBC Capstone Project",
    "link":"https://github.com/jydenberg/HSBC_Capstone",
    "image":"/img/deploysonly.gif",
    "description":"Chatbot designed to communicate basic mortgage, calculator, location, and HSBC related data to customers. Built using Typescipt, SwaggerIO(OpenAPI), and MongoDB.",
    "featured":true,
    "tags":["Java","jQuery","REST APIs","Bamboo","JSON"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"100",
    "sitemap": {"priority" : "0.8"}
}

Addressed pretty significant page load performance issue founde in larger deployments. Eliminates uses of intensive backend query, replacing it with an asynchronous API call against a lucene index. This change reduces page load from from 2+ minutes to nearly instant, with an incredibly responsive UI.
