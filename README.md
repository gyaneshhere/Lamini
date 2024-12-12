      Introduction - Lamini Docs   :root{--md-admonition-icon--note:url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16"><path d="M1 7.775V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 0 1 0 2.474l-5.026 5.026a1.75 1.75 0 0 1-2.474 0l-6.25-6.25A1.75 1.75 0 0 1 1 7.775m1.5 0c0 .066.026.13.073.177l6.25 6.25a.25.25 0 0 0 .354 0l5.025-5.025a.25.25 0 0 0 0-.354l-6.25-6.25a.25.25 0 0 0-.177-.073H2.75a.25.25 0 0 0-.25.25ZM6 5a1 1 0 1 1 0 2 1 1 0 0 1 0-2"/></svg>');}   :root{--md-text-font:"Roboto";--md-code-font:"Roboto Mono"}   \_\_md\_scope=new URL(".",location),\_\_md\_hash=e=>\[...e\].reduce(((e,\_)=>(e<<5)-e+\_.charCodeAt(0)),0),\_\_md\_get=(e,\_=localStorage,t=\_\_md\_scope)=>JSON.parse(\_.getItem(t.pathname+"."+e)),\_\_md\_set=(e,\_,t=localStorage,a=\_\_md\_scope)=>{try{t.setItem(a.pathname+"."+e,JSON.stringify(\_))}catch(e){}} function \_\_md\_analytics(){function e(){dataLayer.push(arguments)}window.dataLayer=window.dataLayer||\[\],e("js",new Date),e("config","G-6ZQD4KPE0G"),document.addEventListener("DOMContentLoaded",(function(){document.forms.search&&document.forms.search.query.addEventListener("blur",(function(){this.value&&e("event","search",{search\_term:this.value})}));document$.subscribe((function(){var t=document.forms.feedback;if(void 0!==t)for(var a of t.querySelectorAll("\[type=submit\]"))a.addEventListener("click",(function(a){a.preventDefault();var n=document.location.pathname,d=this.getAttribute("data-md-value");e("event","feedback",{page:n,data:d}),t.firstElementChild.disabled=!0;var r=t.querySelector(".md-feedback\_\_note \[data-md-value='"+d+"'\]");r&&(r.hidden=!1)})),t.hidden=!1})),location$.subscribe((function(t){e("config","G-6ZQD4KPE0G",{page\_path:t.pathname})}))}));var t=document.createElement("script");t.async=!0,t.src="https://www.googletagmanager.com/gtag/js?id=G-6ZQD4KPE0G",document.getElementById("\_\_analytics").insertAdjacentElement("afterEnd",t)} "undefined"!=typeof \_\_md\_analytics&&\_\_md\_analytics()  

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
