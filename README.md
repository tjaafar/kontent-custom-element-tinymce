# TinyMCE Editor Custom Element for Kentico Kontent

This is a [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) that allows users to edit rich text using the TinyMCE editor.

![Screenshot of custom element](TinyMCE.png)

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Setup TinyMCE
    1. Sign up for an account on <https://www.tiny.cloud/>
    1. Choose the `Javascript` integration
    1. Add your secure ppublic host to the allowed hosts
    1. Replace the script on [index.html line 9](index.html) with the one TinyMCE provides you
    1. Redeploy the code to your secure public host
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/kontent-custom-element-tinymce)

## What is Saved?

The value is returned as a string of HTML.

## Contributors

Originally contributed by [@Enngage](https://github.com/Enngage)
