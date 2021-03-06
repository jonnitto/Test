# Neos-Skeleton Features

#### Main features

 - A powerfull best practise layout rendering machanism
 - Best practise folder and naming structure
 - A well rounded set of packages to build typical websites

#### Further boilerplate features

 - [YAML Constraints](https://www.youtube.com/watch?v=ZCRYsYvxXFI) to easily manage where node types should be available
 - It provides the most used smartphone and tablet sizes as preview modes
 - All rendering is based on Fusion and AFX

#### Features via required packages

 - [neos/seo](https://github.com/neos/neos-seo) allows your to configure SEO and social media settings
 - [neos/redirecthandler-neosadapter](https://github.com/neos/redirecthandler-neosadapter) automatically creates a redirect when you change/move a page
 - [neos/neos-googleanalytics](https://github.com/neos/neos-googleanalytics) adds your Google Analtics tracking code
 - [carbon/compression](https://github.com/CarbonPackages/Carbon.Compression) compresses the HTML output
 - [shel/neos-hyphens](https://github.com/Sebobo/Shel.Neos.Hyphens) allows editors to add shy characters
 - [codeq/unicodenormalizer](https://github.com/code-q-web-factory/neos-unicodenormalizer) handles broken German Umlaute
 - [flowpack/cachebuster](https://github.com/Flowpack/Flowpack.CacheBuster) adds automatic cache busting for assets in the frontend
 - ~~[moc/notfound](https://github.com/mocdk/MOC.NotFound) loads a normal editable page for displaying a 404 error~~ 4xx error page based on Neos 4.3 error rendering instead
 - [neos/nodetypes-contentreferences](https://github.com/neos/nodetypes-contentreferences) provides a reference content node type
 
#### Development features via required packages

 - [carbon/link](https://github.com/jonnitto/Carbon.Link) provides powerfull link helpers
 - [sitegeist/silhouettes](https://github.com/sitegeist/Sitegeist.Silhouettes) let's you preconfigure property-silhouettes that can be applied to various properties of multiple NodeTypes in a better way then mixins.
 - [carbon/includeassets](https://github.com/CarbonPackages/Carbon.IncludeAssets) provides an easy way to include your assets (css, js)
