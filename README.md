# Kentico Kontent type selector custom element

This [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) for [Kentico Kontent](https://kontent.ai) gives editors a way to select [content types](https://docs.kontent.ai/tutorials/manage-kontent/content-modeling/create-and-delete-content-types) from current project.

## Features

- Display optional debug panel for diagnostics

## Quick testing

If you're interested in trying this out without deploying it yourself, you can use [kontent-custom-element-type-selector.netlify.app](kontent-custom-element-type-selector.netlify.app) This is the deployed version of the master branch in this repo. **This should only be used for quick testing as it is subject to change**

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your account as well.


[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Simply007/kontent-custom-element-type-selector)

## Configuring the Custom Element

You will need to add the custom element to a content type filling in the hosted code URL and the JSON parameters (see below for details).

The JSON parameters required as as follows:

| Name     | Type   | Description |
| -------- | ------ | ----------- |
| debug    | boolean | (Optional) If present and set to true the debug panel will activate when editing a content item. |

Sample parameters JSON:

```json
{
  "debug": true
}
```

## Developing

### Initial project setup

```console
npm install
```

### Compiles and hot-reloads for development

```console
npm run serve
```

### Compiles and minifies for production

```console
npm run build
```

### Lints and fixes files

```console
npm run lint
```

### Customize Vue CLI configuration

See [Vue CLI Configuration Reference](https://cli.vuejs.org/config/).
