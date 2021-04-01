![buildinamsterdam logo](https://github.com/StanBankras/weekly-nerd-2021/blob/master/img/buildinamsterdam/logo.png?raw=true)

# Build In Amsterdam presentation notes
Presentation by Fenna de Wilde

* "We believe conversion is driven by emotion"

## Stack
* NextJS (REact)
* Contentful
* Vercel

## Animation tips
![buildinamsterdam animation](https://github.com/StanBankras/weekly-nerd-2021/blob/master/img/buildinamsterdam/animation.png?raw=true)

* Optimize for the browser
* Use opacity & transform as much as possible
* transform: translateZ or translate3d to trigger GPU
* visibility: hidden instead of opacity: 0 can be a live safer
* Cache values that stay the same
* request animation frames
* Watch out for style invalidation
* Performance tab can be useful to check your frames/second and animation phases

