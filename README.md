      Introduction - Lamini Docs  
[Skip to content](#welcome-to-lamini)

[![logo](assets/logo.png)](. "Lamini Docs")

Lamini Docs

Introduction

  

var palette=\_\_md\_get("\_\_palette");if(palette&&palette.color){if("(prefers-color-scheme)"===palette.color.media){var media=matchMedia("(prefers-color-scheme: light)"),input=document.querySelector(media.matches?"\[data-md-color-media='(prefers-color-scheme: light)'\]":"\[data-md-color-media='(prefers-color-scheme: dark)'\]");palette.color.media=input.getAttribute("data-md-color-media"),palette.color.scheme=input.getAttribute("data-md-color-scheme"),palette.color.primary=input.getAttribute("data-md-color-primary"),palette.color.accent=input.getAttribute("data-md-color-accent")}for(var\[key,value\]of Object.entries(palette.color))document.body.setAttribute("data-md-color-"+key,value)}

Initializing search

*   [Documentation](.)
*   [Python SDK](lamini_python_class/lamini/)
*   [REST API](api/)

 [![logo](assets/logo.png)](. "Lamini Docs")Lamini Docs

*    Documentation
    
    Documentation
    
    *    Get Started
        
        Get Started
        
        *    [Introduction](.)
        *   [Quick Start](quick_start/)
        *   [Examples 🔗](https://github.com/lamini-ai/lamini-examples)
        *   [About](about/)
        *   [FAQ](faq/)
        
    *    Applications
        
        Applications
        
        *   [Retrieval Augmented Generation (RAG) 🔗](https://github.com/lamini-ai/lamini-examples/blob/main/04_rag_tuning/README.md)
        *   [Generation Pipeline 🔗](https://github.com/lamini-ai/lamini-examples/blob/main/05_data_pipeline/README.md)
        
    *   [Classifier Agent Toolkit](cat/)
    *    Tuning
        
        Tuning
        
        *   [Memory Tuning](tuning/memory_tuning/)
        *   [Hyperparameters](tuning/hyperparameters/)
        *   [Large Data Files](tuning/large_data_files/)
        *   [Evaluation](tuning/evaluation/)
        
    *    Inference
        
        Inference
        
        *   [Prompt Templates](inference/prompt_templates/)
        *   [JSON Output](inference/json_output/)
        *   [Batching](inference/batching/)
        *   [Streaming](inference/streaming/)
        *   [Performance](inference/performance/)
        
    *    Platform Concepts
        
        Platform Concepts
        
        *   [API Auth](authenticate/)
        *   [Models](models/)
        *   [Playground](inference/playground/)
        *   [Tuning Dashboard](tuning/dashboard/)
        
    *    Self-Managed
        
        Self-Managed
        
        *   [Kubernetes Install](self_managed/kubernetes_install/)
        *   [AWS EKS Setup](self_managed/aws_eks_setup/)
        *   [OIDC User Auth](self_managed/OIDC/)
        *   [Model Management](self_managed/model_management/)
        
    
*    Python SDK
    
    Python SDK
    
    *   [lamini](lamini_python_class/lamini/)
    
*   [REST API](api/)

Welcome to Lamini 🦙
====================

Lamini is an integrated LLM inference and tuning platform. You can tune models that achieve exceptional factual accuracy while minimizing latency and cost.

Lamini Self-Managed runs in your environment - even air-gapped - or you can use our GPUs with our On-Demand and Reserved options.

Goal 🏁

Go to 🔗

2 steps to start using LLMs on Lamini On-Demand ☁️

[Quick Start](/quick_start)

95% accuracy and beyond 🧠

[Memory Tuning](/tuning/memory_tuning/)

LLM inference that's 100% guaranteed to match your schema 💯

[JSON Output](/inference/json_output/)

Run Lamini on your own GPUs 🔒

[Kubernetes Installation](/self_managed/kubernetes_install)

What makes Lamini unique? ✨

[About](/about)

Use cases and recipes 🥘

[Examples](https://github.com/lamini-ai/lamini-examples/)

Having trouble? [Contact us](https://www.lamini.ai/contact)!

var target=document.getElementById(location.hash.slice(1));target&&target.name&&(target.checked=target.name.startsWith("\_\_tabbed\_"))

[

Next

Quick Start

](quick_start/)

Made with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

{"base": ".", "features": \["content.code.copy", "navigation.instant", "navigation.tracking", "navigation.expand", "navigation.footer", "navigation.tabs", "navigation.tabs.sticky"\], "search": "assets/javascripts/workers/search.6ce7567c.min.js", "translations": {"clipboard.copied": "Copied to clipboard", "clipboard.copy": "Copy to clipboard", "search.result.more.one": "1 more on this page", "search.result.more.other": "# more on this page", "search.result.none": "No matching documents", "search.result.one": "1 matching document", "search.result.other": "# matching documents", "search.result.placeholder": "Type to start searching", "search.result.term.missing": "Missing", "select.version": "Select version"}} document$.subscribe(() => { window.update\_swagger\_ui\_iframe\_height = function (id) { var iFrameID = document.getElementById(id); if (iFrameID) { full\_height = (iFrameID.contentWindow.document.body.scrollHeight + 80) + "px"; iFrameID.height = full\_height; iFrameID.style.height = full\_height; } } let iframe\_id\_list = \[\] var iframes = document.getElementsByClassName("swagger-ui-iframe"); for (var i = 0; i < iframes.length; i++) { iframe\_id\_list.push(iframes\[i\].getAttribute("id")) } let ticking = true; document.addEventListener('scroll', function(e) { if (!ticking) { window.requestAnimationFrame(()=> { let half\_vh = window.innerHeight/2; for(var i = 0; i < iframe\_id\_list.length; i++) { let element = document.getElementById(iframe\_id\_list\[i\]) if(element==null){ return } let diff = element.getBoundingClientRect().top if(element.contentWindow.update\_top\_val){ element.contentWindow.update\_top\_val(half\_vh - diff) } } ticking = false; }); ticking = true; } }); const dark\_scheme\_name = "slate" window.scheme = document.body.getAttribute("data-md-color-scheme") const options = { attributeFilter: \['data-md-color-scheme'\], }; function color\_scheme\_callback(mutations) { for (let mutation of mutations) { if (mutation.attributeName === "data-md-color-scheme") { scheme = document.body.getAttribute("data-md-color-scheme") var iframe\_list = document.getElementsByClassName("swagger-ui-iframe") for(var i = 0; i < iframe\_list.length; i++) { var ele = iframe\_list.item(i); if (ele) { if (scheme === dark\_scheme\_name) { ele.contentWindow.enable\_dark\_mode(); } else { ele.contentWindow.disable\_dark\_mode(); } } } } } } observer = new MutationObserver(color\_scheme\_callback); observer.observe(document.body, options); })
