Refactor project for client Horiseon
========================================

Objectives
-------------
    Ensure all links work correctly
    Consolidate css selectors and properties and organize to follow html flow
    Include comments before elements/sections of page    
    Replace <div> with semantic HTML elements
    Form logical structure of HTML elements
    Add descriptive alt attributes to all images
    Edit title of page to be concise, yet descriptive

Summary of modifications
---------------------------
    Ensure all links work correctly
        Fixed link for "search-engine-optimization" by adding id to match link in nav section

    Consolidate css selectors and properties and organize to follow html flow
        Remove repetive classes with same property settings
        Defined class services to replace existing 3 and also updated styles of elements within the services class, consolidating to just 1 for img and h2

        Defined class benefit-sub to replace existing 3 and also updated styles of elements 
        within the benefit-sub class, consolidating to just 1 for img and h3

    Include comments before elements/sections of page
        Added comments to html and css where necessary 
        Added comments regarding changes from original files
    
    Replace <div> with semantic HTML elements
        header,nav,figure,main,section,aside,footer used throughout html instead of div
    
    Form logical structure of HTML elements
        Modified css file to match flow of html, moving services class above benefits
   
    Add descriptive alt attributes to all images
        Add alt text descriptions to all images

    Edit title of page to be concise, yet descriptive
        Changed from 'website' to company name and key services


    ********Additonal changes************
    Changed <nav> font-size in css to be 24 instead of 20
    Changed color and capitalized SEO in Horiseon to stand out
    Moved url of "hero" to img in html and left width as 100% with margin-bottom to scale image better on different size screens    
