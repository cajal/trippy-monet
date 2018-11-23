var md = require('markdown-it')({
  html: true,
  linkify: true,
  typography: true
}).use(require('markdown-it-video', { // <-- this use(package_name) is required
  youtube: { width: 640, height: 390 },
  vimeo: { width: 500, height: 281 },
  vine: { width: 600, height: 600, embed: 'simple' },
  prezi: { width: 550, height: 400 }
}));

# Stimuli for fast mapping of visual response properties 

This repository describes two visual stimuli used in functional descriptions of cortical circuits. 


, *Trippy* and *Monet*, 

[SfN 2018 Poster](yatsenko-SfN2018-lowres.pdf)

@[vimeo](249686342)
