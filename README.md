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
