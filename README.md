<!DOCTYPE html>
<html lang="en"><head>
<script src="Slides_CSI_2023_2_files/libs/clipboard/clipboard.min.js"></script>
<script src="Slides_CSI_2023_2_files/libs/quarto-html/tabby.min.js"></script>
<script src="Slides_CSI_2023_2_files/libs/quarto-html/popper.min.js"></script>
<script src="Slides_CSI_2023_2_files/libs/quarto-html/tippy.umd.min.js"></script>
<link href="Slides_CSI_2023_2_files/libs/quarto-html/tippy.css" rel="stylesheet">
<link href="Slides_CSI_2023_2_files/libs/quarto-html/quarto-html.min.css" rel="stylesheet" data-mode="light">
<link href="Slides_CSI_2023_2_files/libs/quarto-html/quarto-syntax-highlighting.css" rel="stylesheet" id="quarto-text-highlighting-styles"><meta charset="utf-8">
  <meta name="generator" content="quarto-1.2.269">

  <title>slides_csi_2023_2</title>
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, minimal-ui">
  <link rel="stylesheet" href="Slides_CSI_2023_2_files/libs/revealjs/dist/reset.css">
  <link rel="stylesheet" href="Slides_CSI_2023_2_files/libs/revealjs/dist/reveal.css">
  <style>
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    div.columns{display: flex; gap: min(4vw, 1.5em);}
    div.column{flex: auto; overflow-x: auto;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
    ul.task-list li input[type="checkbox"] {
      width: 0.8em;
      margin: 0 0.8em 0.2em -1.6em;
      vertical-align: middle;
    }
  </style>
  <link rel="stylesheet" href="Slides_CSI_2023_2_files/libs/revealjs/dist/theme/quarto.css" id="theme">
  <link href="Slides_CSI_2023_2_files/libs/revealjs/plugin/quarto-line-highlight/line-highlight.css" rel="stylesheet">
  <link href="Slides_CSI_2023_2_files/libs/revealjs/plugin/reveal-menu/menu.css" rel="stylesheet">
  <link href="Slides_CSI_2023_2_files/libs/revealjs/plugin/reveal-menu/quarto-menu.css" rel="stylesheet">
  <link href="Slides_CSI_2023_2_files/libs/revealjs/plugin/quarto-support/footer.css" rel="stylesheet">
  <style type="text/css">

  .callout {
    margin-top: 1em;
    margin-bottom: 1em;  
    border-radius: .25rem;
  }

  .callout.callout-style-simple { 
    padding: 0em 0.5em;
    border-left: solid #acacac .3rem;
    border-right: solid 1px silver;
    border-top: solid 1px silver;
    border-bottom: solid 1px silver;
    display: flex;
  }

  .callout.callout-style-default {
    border-left: solid #acacac .3rem;
    border-right: solid 1px silver;
    border-top: solid 1px silver;
    border-bottom: solid 1px silver;
  }

  .callout .callout-body-container {
    flex-grow: 1;
  }

  .callout.callout-style-simple .callout-body {
    font-size: 1rem;
    font-weight: 400;
  }

  .callout.callout-style-default .callout-body {
    font-size: 0.9rem;
    font-weight: 400;
  }

  .callout.callout-captioned.callout-style-simple .callout-body {
    margin-top: 0.2em;
  }

  .callout:not(.callout-captioned) .callout-body {
      display: flex;
  }

  .callout:not(.no-icon).callout-captioned.callout-style-simple .callout-content {
    padding-left: 1.6em;
  }

  .callout.callout-captioned .callout-header {
    padding-top: 0.2em;
    margin-bottom: -0.2em;
  }

  .callout.callout-captioned .callout-caption  p {
    margin-top: 0.5em;
    margin-bottom: 0.5em;
  }
    
  .callout.callout-captioned.callout-style-simple .callout-content  p {
    margin-top: 0;
  }

  .callout.callout-captioned.callout-style-default .callout-content  p {
    margin-top: 0.7em;
  }

  .callout.callout-style-simple div.callout-caption {
    border-bottom: none;
    font-size: .9rem;
    font-weight: 600;
    opacity: 75%;
  }

  .callout.callout-style-default  div.callout-caption {
    border-bottom: none;
    font-weight: 600;
    opacity: 85%;
    font-size: 0.9rem;
    padding-left: 0.5em;
    padding-right: 0.5em;
  }

  .callout.callout-style-default div.callout-content {
    padding-left: 0.5em;
    padding-right: 0.5em;
  }

  .callout.callout-style-simple .callout-icon::before {
    height: 1rem;
    width: 1rem;
    display: inline-block;
    content: "";
    background-repeat: no-repeat;
    background-size: 1rem 1rem;
  }

  .callout.callout-style-default .callout-icon::before {
    height: 0.9rem;
    width: 0.9rem;
    display: inline-block;
    content: "";
    background-repeat: no-repeat;
    background-size: 0.9rem 0.9rem;
  }

  .callout-caption {
    display: flex
  }
    
  .callout-icon::before {
    margin-top: 1rem;
    padding-right: .5rem;
  }

  .callout.no-icon::before {
    display: none !important;
  }

  .callout.callout-captioned .callout-body > .callout-content > :last-child {
    margin-bottom: 0.5rem;
  }

  .callout.callout-captioned .callout-icon::before {
    margin-top: .5rem;
    padding-right: .5rem;
  }

  .callout:not(.callout-captioned) .callout-icon::before {
    margin-top: 1rem;
    padding-right: .5rem;
  }

  /* Callout Types */

  div.callout-note {
    border-left-color: #4582ec !important;
  }

  div.callout-note .callout-icon::before {
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAIKADAAQAAAABAAAAIAAAAACshmLzAAAEU0lEQVRYCcVXTWhcVRQ+586kSUMMxkyaElstCto2SIhitS5Ek8xUKV2poatCcVHtUlFQk8mbaaziwpWgglJwVaquitBOfhQXFlqlzSJpFSpIYyXNjBNiTCck7x2/8/LeNDOZxDuEkgOXe++553zfefee+/OYLOXFk3+1LLrRdiO81yNqZ6K9cG0P3MeFaMIQjXssE8Z1JzLO9ls20MBZX7oG8w9GxB0goaPrW5aNMp1yOZIa7Wv6o2ykpLtmAPs/vrG14Z+6d4jpbSKuhdcSyq9wGMPXjonwmESXrriLzFGOdDBLB8Y6MNYBu0dRokSygMA/mrun8MGFN3behm6VVAwg4WR3i6FvYK1T7MHo9BK7ydH+1uurECoouk5MPRyVSBrBHMYwVobG2aOXM07sWrn5qgB60rc6mcwIDJtQrnrEr44kmy+UO9r0u9O5/YbkS9juQckLed3DyW2XV/qWBBB3ptvI8EUY3I9p/67OW+g967TNr3Sotn3IuVlfMLVnsBwH4fsnebJvyGm5GeIUA3jljERmrv49SizPYuq+z7c2H/jlGC+Ghhupn/hcapqmcudB9jwJ/3jvnvu6vu5lVzF1fXyZuZZ7U8nRmVzytvT+H3kilYvH09mLWrQdwFSsFEsxFVs5fK7A0g8gMZjbif4ACpKbjv7gNGaD8bUrlk8x+KRflttr22JEMRUbTUwwDQScyzPgedQHZT0xnx7ujw2jfVfExwYHwOsDTjLdJ2ebmeQIlJ7neo41s/DrsL3kl+W2lWvAga0tR3zueGr6GL78M3ifH0rGXrBC2aAR8uYcIA5gwV8zIE8onoh8u0Fca/ciF7j1uOzEnqcIm59sEXoGc0+z6+H45V1CvAvHcD7THztu669cnp+L0okAeIc6zjbM/24LgGM1gZk7jnRu1aQWoU9sfUOuhrmtaPIO3YY1KLLWZaEO5TKUbMY5zx8W9UJ6elpLwKXbsaZ4EFl7B4bMtDv0iRipKoDQT2sNQI9b1utXFdYisi+wzZ/ri/1m7QfDgEuvgUUEIJPq3DhX/5DWNqIXDOweC2wvIR90Oq3lDpdMIgD2r0dXvGdsEW5H6x6HLRJYU7C69VefO1x8Gde1ZFSJLfWS1jbCnhtOPxmpfv2LXOA2Xk2tvnwKKPFuZ/oRmwBwqRQDcKNeVQkYcOjtWVBuM/JuYw5b6isojIkYxyYAFn5K7ZBF10fea52y8QltAg6jnMqNHFBmGkQ1j+U43HMi2xMar1Nv0zGsf1s8nUsmUtPOOrbFIR8bHFDMB5zL13Gmr/kGlCkUzedTzzmzsaJXhYawnA3UmARpiYj5ooJZiUoxFRtK3X6pgNPv+IZVPcnwbOl6f+aBaO1CNvPW9n9LmCp01nuSaTRF2YxHqZ8DYQT6WsXT+RD6eUztwYLZ8rM+rcPxamv1VQzFUkzFXvkiVrySGQgJNvXHJAxiU3/NwiC03rSf05VBaPtu/Z7/B8Yn/w7eguloAAAAAElFTkSuQmCC');
  }

  div.callout-note.callout-style-default .callout-caption {
    background-color: #dae6fb
  }

  div.callout-important {
    border-left-color: #d9534f !important;
  }

  div.callout-important .callout-icon::before {
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAIKADAAQAAAABAAAAIAAAAACshmLzAAAEKklEQVRYCcVXTWhcVRS+575MJym48A+hSRFr00ySRQhURRfd2HYjk2SSTokuBCkU2o0LoSKKraKIBTcuFCoidGFD08nkBzdREbpQ1EDNIv8qSGMFUboImMSZd4/f9zJv8ibJMC8xJQfO3HPPPef7zrvvvnvviIkpC9nsw0UttFunbUhpFzFtarSd6WJkStVMw5xyVqYTvkwfzuf/5FgtkVoB0729j1rjXwThS7Vio+Mo6DNnvLfahoZ+i/o32lULuJ3NNiz7q6+pyAUkJaFF6JwaM2lUJlV0MlnQn5aTRbEu0SEqHUa0A4AdiGuB1kFXRfVyg5d87+Dg4DL6m2TLAub60ilj7A1Ec4odSAc8X95sHh7+ZRPCFo6Fnp7HfU/fBng/hi10CjCnWnJjsxvDNxWw0NfV6Rv5GgP3I3jGWXumdTD/3cbEOP2ZbOZp69yniG3FQ9z1jD7bnBu9Fc2tKGC2q+uAJOQHBDRiZX1x36o7fWBs7J9ownbtO+n0/qWkvW7UPIfc37WgT6ZGR++EOJyeQDSb9UB+DZ1G6DdLDzyS+b/kBCYGsYgJbSQHuThGKRcw5xdeQf8YdNHsc6ePXrlSYMBuSIAFTGAtQo+VuALo4BX83N190NWZWbynBjhOHsmNfFWLeL6v+ynsA58zDvvAC8j5PkbOcXCMg2PZFk3q8MjI7WAG/Dp9AwP7jdGBOOQkAvlFUB+irtm16I1Zw9YBcpGTGXYmk3kQIC/Cds55l+iMI3jqhjAuaoe+am2Jw5GT3Nbz3CkE12NavmzN5+erJW7046n/CH1RO/RVa8lBLozXk9uqykkGAyRXLWlLv5jyp4RFsG5vGVzpDLnIjTWgnRy2Rr+tDKvRc7Y8AyZq10jj8DqXdnIRNtFZb+t/ZRtXcDiVnzpqx8mPcDWxgARUqx0W1QB9MeUZiNrV4qP+Ehc+BpNgATsTX8ozYKL2NtFYAHc84fG7ndxUPr+AR/iQSns7uSUufAymwDOb2+NjK27lEFocm/EE2WpyIy/Hi66MWuMKJn8RvxIcj87IM5Vh9663ziW36kR0HNenXuxmfaD8JC7tfKbrhFr7LiZCrMjrzTeGx+PmkosrkNzW94ObzwocJ7A1HokLolY+AvkTiD/q1H0cN48c5EL8Crkttsa/AXQVDmutfyku0E7jShx49XqV3MFK8IryDhYVbj7Sj2P2eBxwcXoe8T8idsKKPRcnZw1b+slFTubwUwhktrfnAt7J++jwQtLZcm3sr9LQrjRzz6cfMv9aLvgmnAGvpoaGLxM4mAEaLV7iAzQ3oU0IvD5x9ix3yF2RAAuYAOO2f7PEFWCXZ4C9Pb2UsgDeVnFSpbFK7/IWu7TPTvBqzbGdCHOJQSxiEjt6IyZmxQyEJHv6xyQsYk//moVFsN2zP6fRImjfq7/n/wFDguUQFNEwugAAAABJRU5ErkJggg==');
  }

  div.callout-important.callout-style-default .callout-caption {
    background-color: #f7dddc
  }

  div.callout-warning {
    border-left-color: #f0ad4e !important;
  }

  div.callout-warning .callout-icon::before {
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAIKADAAQAAAABAAAAIAAAAACshmLzAAAETklEQVRYCeVWW2gcVRg+58yaTUnizqbipZeX4uWhBEniBaoUX1Ioze52t7sRq6APio9V9MEaoWlVsFasRq0gltaAPuxms8lu0gcviE/FFOstVbSIxgcv6SU7EZqmdc7v9+9mJtNks51NTUH84ed889/PP+cmxP+d5FIbMJmNbpREu4WUkiTtCicKny0l1pIKmBzovF2S+hIJHX8iEu3hZJ5lNZGqyRrGSIQpq15AzF28jgpeY6yk6GVdrfFqdrD6Iw+QlB8g0YS2g7dyQmXM/IDhBhT0UCiRf59lfqmmDvzRt6kByV/m4JjtzuaujMUM2c5Z2d6JdKrRb3K2q6mA+oYVz8JnDdKPmmNthzkAk/lN63sYPgevrguc72aZX/L9C6x09GYyxBgCX4NlvyGUHOKELlm5rXeR1kchuChJt4SSwyddZRXgvwMGvYo4QSlk3/zkHD8UHxwVJA6zjZZqP8v8kK8OWLnIZtLyCAJagYC4rTGW/9Pqj92N/c+LUaAj27movwbi19tk/whRCIE7Q9vyI6yvRpftAKVTdUjOW40X3h5OXsKCdmFcx0xlLJoSuQngnrJe7Kcjm4OMq9FlC7CMmScQANuNvjfP3PjGXDBaUQmbp296S5L4DrpbrHN1T87ZVEZVCzg1FF0Ft+dKrlLukI+/c9ENo+TvlTDbYFvuKPtQ9+l052rXrgKoWkDAFnvh0wTOmYn8R5f4k/jN/fZiCM1tQx9jQQ4ANhqG4hiL0qIFTGViG9DKB7GYzgubnpofgYRwO+DFjh0Zin2m4b/97EDkXkc+f6xYAPX0KK2I/7fUQuwzuwo/L3AkcjugPNixC8cHf0FyPjWlItmLxWw4Ou9YsQCr5fijMGoD/zpdRy95HRysyXA74MWOnscpO4j2y3HAVisw85hX5+AFBRSHt4ShfLFkIMXTqyKFc46xdzQM6XbAi702a7sy04J0+feReMFKp5q9esYLCqAZYw/k14E/xcLLsFElaornTuJB0svMuJINy8xkIYuL+xPAlWRceH6+HX7THJ0djLUom46zREu7tTkxwmf/FdOZ/sh6Q8qvEAiHpm4PJ4a/doJe0gH1t+aHRgCzOvBvJedEK5OFE5jpm4AGP2a8Dxe3gGJ/pAutug9Gp6he92CsSsWBaEcxGx0FHytmIpuqGkOpldqNYQK8cSoXvd+xLxXADw0kf6UkJNFtdo5MOgaLjiQOQHcn+A6h5NuL2s0qsC2LOM75PcF3yr5STuBSAcGG+meA14K/CI21HcS4LBT6tv0QAh8Dr5l93AhZzG5ZJ4VxAqdZUEl9z7WJ4aN+svMvwHHL21UKTd1mqvChH7/Za5xzXBBKrUcB0TQ+Ulgkfbi/H/YT5EptrGzsEK7tR1B7ln9BBwckYfMiuSqklSznIuoIIOM42MQO+QnduCoFCI0bpkzjCjddHPN/F+2Yu+sd9bKNpVwHhbS3LluK/0zgfwD0xYI5dXuzlQAAAABJRU5ErkJggg==');
  }

  div.callout-warning.callout-style-default .callout-caption {
    background-color: #fcefdc
  }

  div.callout-tip {
    border-left-color: #02b875 !important;
  }

  div.callout-tip .callout-icon::before {
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAIKADAAQAAAABAAAAIAAAAACshmLzAAADr0lEQVRYCe1XTWgTQRj9ZjZV8a9SPIkKgj8I1bMHsUWrqYLVg4Ue6v9BwZOxSYsIerFao7UiUryIqJcqgtpimhbBXoSCVxUFe9CTiogUrUp2Pt+3aUI2u5vdNh4dmMzOzHvvezuz8xNFM0mjnbXaNu1MvFWRXkXEyE6aYOYJpdW4IXuA4r0fo8qqSMDBU0v1HJUgVieAXxzCsdE/YJTdFcVIZQNMyhruOMJKXYFoLfIfIvVIMWdsrd+Rpd86ZmyzzjJmLStqRn0v8lzkb4rVIXvnpScOJuAn2ACC65FkPzEdEy4TPWRLJ2h7z4cArXzzaOdKlbOvKKX25Wl00jSnrwVxAg3o4dRxhO13RBSdNvH0xSARv3adTXbBdTf64IWO2vH0LT+cv4GR1DJt+DUItaQogeBX/chhbTBxEiZ6gftlDNXTrvT7co4ub5A6gp9HIcHvzTa46OS5fBeP87Qm0fQkr4FsYgVQ7Qg+ZayaDg9jhg1GkWj8RG6lkeSacrrHgDaxdoBiZPg+NXV/KifMuB6//JmYH4CntVEHy/keA6x4h4CU5oFy8GzrBS18cLJMXcljAKB6INjWsRcuZBWVaS3GDrqB7rdapVIeA+isQ57Eev9eCqzqOa81CY05VLd6SamW2wA2H3SiTbnbSxmzfp7WtKZkqy4mdyAlGx7ennghYf8voqp9cLSgKdqNfa6RdRsAAkPwRuJZNbpByn+RrJi1RXTwdi8RQF6ymDwGMAtZ6TVE+4uoKh+MYkcLsT0Hk8eAienbiGdjJHZTpmNjlbFJNKDVAp2fJlYju6IreQxQ08UJDNYdoLSl6AadO+fFuCQqVMB1NJwPm69T04Wv5WhfcWyfXQB+wXRs1pt+nCknRa0LVzSA/2B+a9+zQJadb7IyyV24YAxKp2Jqs3emZTuNnKxsah+uabKbMk7CbTgJx/zIgQYErIeTKRQ9yD9wxVof5YolPHqaWo7TD6tJlh7jQnK5z2n3+fGdggIOx2kaa2YI9QWarc5Ce1ipNWMKeSG4DysFF52KBmTNMmn5HqCFkwy34rDg05gDwgH3bBi+sgFhN/e8QvRn8kbamCOhgrZ9GJhFDgfcMHzFb6BAtjKpFhzTjwv1KCVuxHvCbsSiEz4CANnj84cwHdFXAbAOJ4LTSAawGWFn5tDhLMYz6nWeU2wJfIhmIJBefcd/A5FWQWGgrWzyORZ3Q6HuV+Jf0Bj+BTX69fm1zWgK7By1YTXchFDORywnfQ7GpzOo6S+qECrsx2ifVQAAAABJRU5ErkJggg==');
  }

  div.callout-tip.callout-style-default .callout-caption {
    background-color: #ccf1e3
  }

  div.callout-caution {
    border-left-color: #fd7e14 !important;
  }

  div.callout-caution .callout-icon::before {
    background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAIKADAAQAAAABAAAAIAAAAACshmLzAAACV0lEQVRYCdVWzWoUQRCuqp2ICBLJXgITZL1EfQDBW/bkzUMUD7klD+ATSHBEfAIfQO+iXsWDxJsHL96EHAwhgzlkg8nBg25XWb0zIb0zs9muYYWkoKeru+vn664fBqElyZNuyh167NXJ8Ut8McjbmEraKHkd7uAnAFku+VWdb3reSmRV8PKSLfZ0Gjn3a6Xlcq9YGb6tADjn+lUfTXtVmaZ1KwBIvFI11rRXlWlatwIAAv2asaa9mlB9wwygiDX26qaw1yYPzFXg2N1GgG0FMF8Oj+VIx7E/03lHx8UhvYyNZLN7BwSPgekXXLribw7w5/c8EF+DBK5idvDVYtEEwMeYefjjLAdEyQ3M9nfOkgnPTEkYU+sxMq0BxNR6jExrAI31H1rzvLEfRIdgcv1XEdj6QTQAS2wtstEALLG1yEZ3QhH6oDX7ExBSFEkFINXH98NTrme5IOaaA7kIfiu2L8A3qhH9zRbukdCqdsA98TdElyeMe5BI8Rs2xHRIsoTSSVFfCFCWGPn9XHb4cdobRIWABNf0add9jakDjQJpJ1bTXOJXnnRXHRf+dNL1ZV1MBRCXhMbaHqGI1JkKIL7+i8uffuP6wVQAzO7+qVEbF6NbS0LJureYcWXUUhH66nLR5rYmva+2tjRFtojkM2aD76HEGAD3tPtKM309FJg5j/K682ywcWJ3PASCcycH/22u+Bh7Aa0ehM2Fu4z0SAE81HF9RkB21c5bEn4Dzw+/qNOyXr3DCTQDMBOdhi4nAgiFDGCinIa2owCEChUwD8qzd03PG+qdW/4fDzjUMcE1ZpIAAAAASUVORK5CYII=');
  }

  div.callout-caution.callout-style-default .callout-caption {
    background-color: #ffe5d0
  }

  </style>
  <style type="text/css">
    .reveal div.sourceCode {
      margin: 0;
      overflow: auto;
    }
    .reveal div.hanging-indent {
      margin-left: 1em;
      text-indent: -1em;
    }
    .reveal .slide:not(.center) {
      height: 100%;
    }
    .reveal .slide.scrollable {
      overflow-y: auto;
    }
    .reveal .footnotes {
      height: 100%;
      overflow-y: auto;
    }
    .reveal .slide .absolute {
      position: absolute;
      display: block;
    }
    .reveal .footnotes ol {
      counter-reset: ol;
      list-style-type: none; 
      margin-left: 0;
    }
    .reveal .footnotes ol li:before {
      counter-increment: ol;
      content: counter(ol) ". "; 
    }
    .reveal .footnotes ol li > p:first-child {
      display: inline-block;
    }
    .reveal .slide ul,
    .reveal .slide ol {
      margin-bottom: 0.5em;
    }
    .reveal .slide ul li,
    .reveal .slide ol li {
      margin-top: 0.4em;
      margin-bottom: 0.2em;
    }
    .reveal .slide ul[role="tablist"] li {
      margin-bottom: 0;
    }
    .reveal .slide ul li > *:first-child,
    .reveal .slide ol li > *:first-child {
      margin-block-start: 0;
    }
    .reveal .slide ul li > *:last-child,
    .reveal .slide ol li > *:last-child {
      margin-block-end: 0;
    }
    .reveal .slide .columns:nth-child(3) {
      margin-block-start: 0.8em;
    }
    .reveal blockquote {
      box-shadow: none;
    }
    .reveal .tippy-content>* {
      margin-top: 0.2em;
      margin-bottom: 0.7em;
    }
    .reveal .tippy-content>*:last-child {
      margin-bottom: 0.2em;
    }
    .reveal .slide > img.stretch.quarto-figure-center,
    .reveal .slide > img.r-stretch.quarto-figure-center {
      display: block;
      margin-left: auto;
      margin-right: auto; 
    }
    .reveal .slide > img.stretch.quarto-figure-left,
    .reveal .slide > img.r-stretch.quarto-figure-left  {
      display: block;
      margin-left: 0;
      margin-right: auto; 
    }
    .reveal .slide > img.stretch.quarto-figure-right,
    .reveal .slide > img.r-stretch.quarto-figure-right  {
      display: block;
      margin-left: auto;
      margin-right: 0; 
    }
  </style>
</head>
<body class="quarto-light">
  <div class="reveal">
    <div class="slides">


<section id="section" class="slide level2" data-background-image="Images/Slide1_Background.png">
<h2></h2>
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 15%; width: 1800px; transform: translate(-50%, -50%)">
<p><span style="color: black; font-size: 90px; font-weight: bold; line-height: 1em; margin: 0px; text-align: justify-all;">Multiscale remote sensing of intertidal vegetation of European coasts in response to natural and anthropogenic pressures.</span></p>
</div>
<!-- ::: {.absolute bottom="0%" left="0%"} -->
<!-- ![](Images/Slide1_Background.png){height="100%"} -->
<!-- ::: -->
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 33%; width: 900px; transform: translate(-50%, -50%)">
<p><span style="color: black;font-size: 60px; font-weight: bold;">Start of the thesis in January 2022</span></p>
</div>
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 50%; width: 800px; transform: translate(-50%, -50%)">
<p><span style="color: black;font-size: 70px; font-weight: bold;">Follow-up meeting</span></p>
</div>
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 55%; width: 800px; transform: translate(-50%, -50%)">
<p><span style="color: black;font-size: 60px; font-weight: bold;">15th of June 2023</span></p>
</div>
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 70%; width: 450px; transform: translate(-50%, -50%)">
<p><span style="color: black; font-size: 60px; font-weight: bold;">Simon Oiry</span></p>
<p><span style="color: black; font-size: 55px; font-weight: bold;">Phd student</span></p>
</div>
<div class="gradient_box" style="text-align: center; position: absolute; left: 50%; top: 90%; width: 700px; transform: translate(-50%, -50%)">
<p><span style="color: black;font-size: 55px; font-weight: bold;">Supervisor : Laurent Barillé</span> <span style="color: black;font-size: 55px; font-weight: bold;">Co-supervisor : Pierre Gernez</span></p>
</div>
<div class="absolute" style="left: 5%; bottom: 35%; ">
<p><img data-src="Images/nantes-universite.png" height="300"></p>
</div>
<div class="absolute" style="bottom: 35%; right: 5%; ">
<p><img data-src="Images/rsbe2.png" height="300"></p>
</div>
</section>
<section id="table-of-contents" class="slide level2" style="font-size: 60px;">
<h2>table of contents</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4 5 6</span></p>
</div>
</div>
<div style="line-height: 3">
<ul>
<li class="fragment"><p><strong>1</strong> Introduction</p></li>
<li class="fragment"><p><strong>2</strong> Hyperspectral to multispectral remote sensing to identify intertidal macrophytes</p></li>
<li class="fragment"><p><strong>3</strong> Drone mapping of intertidal soft bottom habitats across 3 sites along the European Atlantic coast</p></li>
<li class="fragment"><p><strong>4</strong> Spatio-temporal variability of intertidal seagrass meadow across a 23° latitudinal gradient: a study of 12 sites</p></li>
<li class="fragment"><p><strong>5</strong> Additional work parallel to the thesis</p></li>
<li class="fragment"><p><strong>6</strong> Conclusion</p></li>
</ul>
</div>
</section>
<section id="coastal-zone-areas-under-anthropogenic-pressure" class="slide level2" style="font-size: 60px;">
<h2>Coastal zone : areas under anthropogenic pressure</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">1</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="bottom: 3%; right: -8%; ">
<p><img data-src="Images/map_buffer_slide21.png" height="1000"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="bottom: 3%; right: -8%; ">
<p><img data-src="Images/map_density_slide21.png" height="1000"></p>
</div>
<div class="fragment fade-out" data-fragment-index="10">
<div class="fragment fade-in absolute" data-fragment-index="6" style="top: 10%; left: 40%; ">
<p><img data-src="Images/ships_slide2.jpg" height="300"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="7" style="top: 10%; left: 60%; ">
<p><img data-src="Images/oyster_slide2.jpg" height="300"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="8" style="top: 34%; left: 40%; ">
<p><img data-src="Images/fishing_slide2.jpg" height="300"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="9" style="top: 34%; left: 63.5%; ">
<p><img data-src="Images/tourism_slide2.jpg" height="300"></p>
</div>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="11" style="top: 25%; left: 40%; ">
<p><img data-src="Images/CoastalErosion.gif" height="750"></p>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="12" style="top: 25%; left: 40%; ">
<p><img data-src="Images/CoastalArtificialisation.png" height="650"></p>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="13" style="top: 25%; left: 40%; ">
<p><img data-src="Images/GreenTides_Slide1.png" height="500"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="14" style="top: 15%; left: 50%; ">
<p><img data-src="Images/EolienneOffshore.jpg" height="400"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="14" style="top: 15%; left: 76%; ">
<p><img data-src="Images/Agarophyton.jpg" height="400"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="14" style="top: 45%; left: 53%; ">
<p><img data-src="Images/Dredging.jpg" height="600"></p>
</div>
<div class="fragment fade-in" data-fragment-index="1" style="font-size: 50px;">
<ul>
<li>Densely populated areas:</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="font-size: 40px;top: 200px; left: 150px; ">
<ul>
<li>4% of the french territory</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="font-size: 40px;top: 300px; left: 150px; ">
<ul>
<li>10% of the french population</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="font-size: 50px;top: 400px; ">
<div class="fragment fade-out" data-fragment-index="10">
<ul>
<li>Many economic activities:</li>
</ul>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="10" style="font-size: 50px;top: 400px; ">
<ul>
<li>Many anthropogenic pressures:</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="11" style="font-size: 40px;top: 500px; left: 150px; ">
<ul>
<li>Shoreline changes and Coastal Erosion</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="12" style="font-size: 40px;top: 600px; left: 150px; ">
<ul>
<li>Modification of hydrological properties</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="13" style="font-size: 40px;top: 700px; left: 150px; ">
<ul>
<li>Input of nutrients or hazardous substances</li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="13" style="font-size: 40px;top: 850px; left: 1000px; ">
<p><span style="color: black;">Quillien et al.&nbsp;(2015)</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="14" style="font-size: 40px;top: 800px; left: 150px; ">
<ul>
<li>Introduction of energy (Noises, Temperature, vibration…)</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="14" style="font-size: 40px;top: 900px; left: 150px; ">
<ul>
<li>Non-indigenous species introduction</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="14" style="font-size: 40px;top: 1000px; left: 150px; ">
<ul>
<li>Extraction of species by commercial fishing</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="14" style="font-size: 40px;top: 1100px; left: 150px; ">
<ul>
<li>…</li>
</ul>
</div>
</section>
<section id="intertidal-habitats" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Intertidal habitats</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">2</span></p>
</div>
<div class="fragment fade-in absolute" data-id="VideoSoft" data-fragment-index="1" style="top: 30%; left: 0%; ">
<p><video data-src="Videos/P4810662.MP4" height="600" controls=""><a href="Videos/P4810662.MP4">Video</a></video></p>
</div>
<div class="fragment fade-in absolute" data-id="VideoHard" data-fragment-index="1" style="top: 30%; left: 50%; ">
<p><video data-src="Videos/DJI_0076_1.mp4" height="600" controls=""><a href="Videos/DJI_0076_1.mp4">Video</a></video></p>
</div>
<div class="fragment fade-in" data-fragment-index="1">
<ul>
<li>Soft Bottom and Hard Bottom</li>
</ul>
</div>
<div class="fragment absolute fade-in" data-id="TextSoft" data-fragment-index="1" style="left: 2%; bottom: 20%; ">
<p><span style="color: black; font-size: 40px">Aveiro Lagoon, Portugal</span></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="1" style="left: 52%; bottom: 20%; ">
<p><span style="color: black; font-size: 40px">Mesquer, France</span></p>
</div>
</section>
<section id="intertidal-habitats-1" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Intertidal habitats</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">2</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 25%; left: 0%; ">
<p><img data-src="Images/habitat_slides3_all.png" height="900"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="top: 25%; left: 0%; ">
<p><img data-src="Images/habitat_slides3_pheo.png" height="900"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="top: 25%; left: 0%; ">
<p><img data-src="Images/habitat_slides3_pheo_chloro.png" height="900"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="4" style="top: 25%; left: 0%; ">
<p><img data-src="Images/habitat_slides3_pheo_chloro_seagrass.png" height="900"></p>
</div>
<div class="absolute fragment fade-in_then-out" data-fragment-index="5" style="top: 25%; left: 0%; ">
<p><img data-src="Images/habitat_slides3.jpg" height="900"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="6" style="top: 43%; left: 50%; ">
<p><img data-src="Images/MPB_slide3.jpg" height="700"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="7" style="top: 43%; left: 50%; ">
<p><img data-src="Images/eelgrass_slide3.jpg" height="700"></p>
</div>
<div class="fragment fade-out" data-fragment-index="11">
<div class="absolute" data-id="VideoSoft" style="top: 0%; left: 50%; ">
<p><video data-src="Videos/P4810662.MP4" height="400" controls=""><a href="Videos/P4810662.MP4">Video</a></video></p>
</div>
<div class="absolute" data-id="TextSoft" style="top: 27%; left: 52%; ">
<p><span style="color: black; font-size: 30px">Aveiro Lagoon, Portugal</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 70%; left: 48%; ">
<p><img data-src="Images/FishSeagrass.jpg" height="350"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="9" style="top: 43%; left: 48%; ">
<p><img data-src="Images/birds2_slide3.jpg" height="350"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="10" style="top: 70%; left: 70%; ">
<p><img data-src="Images/paper_slide3.png" height="350"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="8" style="top: 37%; left: 48%; ">
<ul>
<li>Nurserey and habitat of many species</li>
</ul>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="12" style="top: 50%; left: 60%; ">
<p><img data-src="Images/European_Commission.svg.png" height="444"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="13" style="top: 33%; left: 50%; ">
<p><img data-src="Images/Arrow.png" height="100"></p>
</div>
<div>
<ul>
<li>Soft Bottom <span style="opacity:0.25">and Hard Bottom</span></li>
</ul>
</div>
<div class="fragment fade-in absolute" data-fragment-index="1" style="top: 16%; ">
<ul>
<li>Multiple classes of vegetation</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="2" style="top: 35%; left: 45%; ">
<ul>
<li>Pheophyceae, Brown algae</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="3" style="top: 35%; left: 45%; ">
<ul>
<li>Pheophyceae, Brown algae</li>
<li>Chloropyceae, Green algae</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="4" style="top: 35%; left: 45%; ">
<ul>
<li>Pheophyceae, Brown algae</li>
<li>Chloropyceae, Green algae</li>
<li>Magnoliopsida, Seagrasses</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="5" style="top: 35%; left: 45%; ">
<ul>
<li>Pheophyceae, Brown algae</li>
<li>Chloropyceae, Green algae</li>
<li>Magnoliopsida, Seagrasses</li>
<li>Bracilariophyceae, Microphytobenthos</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="6" style="top: 37%; left: 48%; ">
<ul>
<li>Protection against erosion</li>
</ul>
</div>
<div class="fragment fade-in-then-out absolute" data-fragment-index="7" style="top: 37%; left: 48%; ">
<ul>
<li>Carbon fixation</li>
</ul>
</div>
<div class="fragment fade-in absolute" data-fragment-index="11" style="top: 10%; left: 52%; ">
<p><span style="font-size: 70px">Improve the protection</span></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="12" style="top: 20%; left: 45%; ">
<ul>
<li>Water Framework Directive (2001)</li>
<li>Marine Strategy Framework Directive (2008)</li>
</ul>
</div>
<div class="fragment fade-in absolute" data-fragment-index="13" style="top: 36%; left: 55%; ">
<p>Good Knowledge of soft bottom intertidal habitats</p>
</div>
</section>
<section id="how-to-monitor-this-ecosystem" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">How to monitor this ecosystem ?</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">3</span></p>
</div>
<div class="fragment fade-in" data-fragment-index="1">
<ul>
<li><em>in situ</em> Survey</li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" data-id="LaurentLisboa" style="top: 20%; left: 20%; ">
<p><img data-src="Images/LaurentLisboa.jpg" height="1000"></p>
</div>
</section>
<section id="how-to-monitor-this-ecosystem-1" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">How to monitor this ecosystem ?</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">3</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="7">
<div class="absolute" data-id="LaurentLisboa" style="top: 7%; left: 45%; ">
<p><img data-src="Images/LaurentLisboa.jpg" height="350"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 7%; left: 71%; ">
<p><img data-src="Images/StudentOntheField.jpg" height="350"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 50%; left: 45%; ">
<p><img data-src="Images/Sentinel2.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 53%; left: 52%; ">
<p><img data-src="Images/Matrice200.png" height="400"></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="7" style="top: 20%; left: 45%; ">
<p><img data-src="Images/bandsvstime.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="8" style="top: 5%; left: 50%; ">
<p><img data-src="Images/EOimplemtation.png" width="900"></p>
</div>
<div class="absolute fragment fade-in" data-id="MullerTable" data-fragment-index="11" style="top: 20%; right: 0%; ">
<p><img data-src="Images/muller_karger_table.png" height="700"></p>
</div>
<div class="fragment fade-out" data-fragment-index="9">
<div>
<ul>
<li><em>in situ</em> Survey</li>
</ul>
</div>
<div class="absolute" style="top: 17%; left: 8%; ">
<p>– <span style="font-size: 50px">Time-consuming</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 22%; left: 8%; ">
<p>– <span style="font-size: 50px">Hard to access</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 27%; left: 8%; ">
<p>– <span style="font-size: 50px">Expensive</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 32%; left: 8%; ">
<p>– <span style="font-size: 50px">Low extent and temporal resolution</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 50%; ">
<ul>
<li>Remote Sensing Survey</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 57%; left: 8%; ">
<p>– <span style="font-size: 50px">Cost effective</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 62%; left: 8%; ">
<p>– <span style="font-size: 50px">Good coverage/Time ratio</span></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="8">
<p><span style="position: absolute; left: 1200px; top: 1150px; height: 110px; width: 785px; background-color: #FFFFFF; padding: 20px; padding-left: 50px; font-size: 20px; text-align: center; color:#292626 ">Papathanasopoulou, E., Simis, S., Alikas, K., Ansper, A., Anttila, S., Jenni, A., Barillé, A.-L., Barillé, L., Brando, V., Bresciani, M., Bučas, M., Gernez, P., Giardino, C., Harin, N., Hommersom, A., Kangro, K., Kauppila, P., Koponen, S., Laanen, M., … Zoffoli, M. L. (2019). Satellite-assisted monitoring of water quality to support the implementation of the Water Framework Directive. In EOMORES white paper. https://doi.org/10.5281/zenodo.3463051</span></p>
</div>
<div class="absolute fragment fade-in" data-id="Mullerlegend" data-fragment-index="12" style="top: 15%; right: 15%; ">
<p><span style="font-size: 40px">Muller-Karger et al.&nbsp;(2018)</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="9" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Pereira2013.png" height="300"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="10" style="top: 40%; left: 0%; width: 40%; ">
<ul>
<li>Standardized measurements or indicators to monitor biodiversity</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="11" style="top: 40%; left: 0%; width: 40%; ">
<ul>
<li>Standardized measurements or indicators to monitor biodiversity</li>
<li>Key metrics to monitor and assess biodiversity changes</li>
</ul>
</div>
</section>
<section id="how-to-monitor-this-ecosystem-2" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">How to monitor this ecosystem ?</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">3</span></p>
</div>
<div class="absolute" data-id="MullerTable" style="top: 13%; left: 15%; ">
<p><img data-src="Images/muller_slide4.png" height="1000"></p>
</div>
<div class="absolute" style="left: 35%; bottom: 3%; ">
<p><img data-src="Images/scale_muller_slide4.png" height="40"></p>
</div>
<div class="absolute" data-id="Mullerlegend" style="top: 8%; right: 15%; ">
<p><span style="font-size: 40px">Table adapted from Muller-Karger et al.&nbsp;(2018)</span></p>
</div>
</section>
<section id="objectives-of-the-thesis" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Objectives of the thesis</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p>1 <span style="opacity:0.25">2 3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">4</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="5">
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="width: 2200px; ">
<ul>
<li><span style="font-size: 60px">Map spatial and temporal variations in plant biodiversity of intertidal zones with a focus on green macrophytes</span></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="width: 2200px; ">
<ul>
<li><span style="font-size: 60px">Map</span> <span style="font-size: 60px; color: red">spatial</span> <span style="font-size: 60px">and temporal variations in plant biodiversity of intertidal zones with a focus on green macrophytes</span></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="width: 2200px; ">
<ul>
<li><span style="font-size: 60px">Map</span> <span style="font-size: 60px; color: red">spatial</span> <span style="font-size: 60px">and</span> <span style="font-size: 60px; color: red">temporal</span> <span style="font-size: 60px">variations in plant biodiversity of intertidal zones with a focus on green macrophytes</span></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 20%; left: 20%; ">
<p><img data-src="Images/matrice200.png" height="300"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 20%; right: 35%; ">
<p><img data-src="Images/Sentinel2.png" height="300"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 25%; right: 10%; ">
<ul>
<li><span style="font-size: 40px">Revisit time: 3 to 5 days</span></li>
<li><span style="font-size: 40px">Archive since 2016</span></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="bottom: 40%; ">
<ul>
<li><span style="font-size: 60px">Analyze natural and human factors responsible for changes.</span></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 60%; left: 0%; ">
<p><img data-src="Images/SST.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 60%; left: 30%; ">
<p><img data-src="Images/MHW.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 60%; left: 65%; ">
<p><img data-src="Images/riverdischarge.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 55%; left: 8%; ">
<p><span style="font-size: 40px">Sea Surface Temperature</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 55%; left: 42%; ">
<p><span style="font-size: 40px">Marine Heat Wave</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 55%; left: 76%; ">
<p><span style="font-size: 40px">River Discharge</span></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 37%; left: 0%; ">
<p><img data-src="Images/workflowthesis_0.png" width="2400"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="6" style="top: 37%; left: 0%; ">
<p><img data-src="Images/workflowthesis_1.png" width="2400"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="7" style="top: 11%; left: 0%; ">
<p><img data-src="Images/workflowthesis_2.png" width="2400"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="8" style="top: 11%; left: 0%; ">
<p><img data-src="Images/workflowthesis_3.png" width="2400"></p>
</div>
<div class="absolute fragment fade-in-" data-fragment-index="9" style="top: 37%; left: 0%; ">
<p><img data-src="Images/workflowthesis_0.png" width="2400"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="9" style="top: 35%; left: -1%; ">
<div class="redbox absolute" style="width: 1700px; height: 300px; ">

</div>
</div>
</section>
<section id="challenges-to-map-intertidal-vegetation" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Challenges to map intertidal vegetation</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1</span> 2 <span style="opacity:0.25">3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">5</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 20%; left: -2%; ">
<p><img data-src="Images/habitat_slides3.jpg" height="800"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" data-id="SpectralSignature" style="top: 25%; right: -5%; ">
<p><img data-src="Images/SpectralSignature.png" height="700"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" data-id="SpectralSignature_Xaxis" style="left: 65%; bottom: 15%; ">
<p><span style="font-size: 40px">Wavelength (nm)</span></p>
</div>
</section>
<section id="challenges-to-map-intertidal-vegetation-1" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Challenges to map intertidal vegetation</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1</span> 2 <span style="opacity:0.25">3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">5</span></p>
</div>
<div class="absolute" style="top: 7%; left: -1%; ">
<p><img data-src="Images/TablePigments.png" height="450"></p>
</div>
<div class="absolute" data-id="SpectralSignature" style="top: 50%; left: 5%; ">
<p><img data-src="Images/SpectralSignature.png" height="550"></p>
</div>
<div class="absolute" data-id="SpectralSignature_Xaxis" style="left: 26%; bottom: 2%; ">
<p><span style="font-size: 35px">Wavelength (nm)</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="left: 62%; bottom: 45%; ">
<p><span style="position: absolute; height: 110px; width: 785px; padding: 20px; padding-left: 50px; font-size: 80px; text-align: center">Green macrophytes share the same pigment composition</span></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="1" style="top: 13.5%; left: -1%; ">
<div class="redbox absolute" style="width: 2250px; height: 81px; ">

</div>
</div>
</section>
<section id="discriminate-green-macrophytes-using-remote-sensing" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Discriminate green macrophytes using remote sensing</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1</span> 2 <span style="opacity:0.25">3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">6</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="8">
<div class="absolute" data-id="SpectralSignature" style="top: 7%; left: -2%; ">
<p><img data-src="Images/SpectralSignature.png" height="500"></p>
</div>
<div class="fragment fade-out" data-fragment-index="2">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 55%; left: 60%; ">
<p><img data-src="Images/Sentinel2.png" height="300"></p>
</div>
<div class="absolute" data-id="ASD" style="top: 60%; left: 0%; ">
<p><img data-src="Images/ASD.png" height="200"></p>
</div>
<div class="absolute" data-id="ASD_text" style="top: 65%; left: 20%; ">
<p><span style="font-size: 35px">Hyperspectral spectroradiometer</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" data-id="ASD_text" style="top: 65%; left: 80%; ">
<p><span style="font-size: 35px">Sentinel-2 constellation</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" data-id="ASD_text" style="top: 70%; left: 80%; ">
<p><span style="font-size: 35px">4 spectral bands</span></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="4">
<div class="absolute fragment fade-in" data-fragment-index="1" data-id="SpectralSignature_S2" style="top: 7%; left: 52%; ">
<p><img data-src="Images/SpectralSignatureS2_10m.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 35%; left: 83%; ">
<p><span style="font-size: 35px">Sentinel-2 10m</span></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="top: 50%; left: 20%; ">
<p><img data-src="Images/BedePaperCover.png" height="600"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" data-id="ASD" style="top: 50%; left: 0%; ">
<p><img data-src="Images/ASD.png" height="200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 65%; left: 0%; ">
<p><span style="font-size: 35px">Hyperspectral spectroradiometer</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 80%; left: 0%; ">
<p>A total of 332 spectra</p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" data-id="ASD" style="top: 45%; left: 25%; ">
<p><img data-src="Images/spectro.jpg" height="650"></p>
</div>
<div class="fragment fade-out" data-fragment-index="5">
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 7%; left: 52%; ">
<p><img data-src="Images/SpectralSignaturePrisma.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 35%; left: 88%; ">
<p><span style="font-size: 35px">Prisma</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 55%; left: 60%; ">
<p><img data-src="Images/Prisma.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 65%; left: 80%; ">
<p>Prisma</p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 70%; left: 80%; ">
<p><span style="font-size: 35px">56 spectral bands</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 73%; left: 80%; ">
<p><span style="font-size: 35px">From 400 nm to 900 nm</span></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="6">
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 7%; left: 52%; ">
<p><img data-src="Images/SpectralSignatureDrone.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 35%; left: 81%; ">
<p><span style="font-size: 35px">Drone’s camera</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 55%; left: 60%; ">
<p><img data-src="Images/Drone_zoom.jpg" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 65%; left: 80%; ">
<p>Micasense MX Dual</p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 70%; left: 80%; ">
<p><span style="font-size: 35px">10 spectral bands</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 73%; left: 80%; ">
<p><span style="font-size: 35px">From 444 nm to 840 nm</span></p>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 7%; left: 52%; ">
<p><img data-src="Images/SpectralSignaturePleiades.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 35%; left: 83%; ">
<p><span style="font-size: 35px">Pleiades</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 55%; left: 65%; ">
<p><img data-src="Images/Pleiades.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 65%; left: 80%; ">
<p>Pleiades</p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 70%; left: 80%; ">
<p><span style="font-size: 35px">4 spectral bands</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 73%; left: 80%; ">
<p><span style="font-size: 35px">From 430 nm to 950 nm</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="7">
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 7%; left: 52%; ">
<p><img data-src="Images/SpectralSignatureS2_20m.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 35%; left: 80%; ">
<p><span style="font-size: 35px">Sentinel-2 20m</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 55%; left: 55%; ">
<p><img data-src="Images/Sentinel2.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 65%; left: 80%; ">
<p>Sentinel-2</p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 70%; left: 80%; ">
<p><span style="font-size: 35px">8 spectral bands</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 73%; left: 80%; ">
<p><span style="font-size: 35px">From 492 nm to 864 nm</span></p>
</div>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 7%; left: 0%; ">
<p><img data-src="Images/Figure5_Bede_Drone.png" height="600"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 53%; left: 0%; ">
<p><img data-src="Images/Figure5_Bede_S210m.png" height="600"></p>
</div>
<div class="fragment fade-out" data-fragment-index="9">
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 7%; left: 40%; ">
<p><img data-src="Images/Figure5_Bede_legend.png" height="100"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 15%; left: 52%; ">
<p><img data-src="Images/SpectralSignatureDrone.png" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 60%; left: 52%; ">
<p><img data-src="Images/SpectralSignatureS2_10m.png" height="500"></p>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="9" style="top: 7%; left: 50%; ">
<p><img data-src="Images/Figure6_Bede.png" height="1200"></p>
</div>
</section>
<section id="discriminate-green-macrophytes-using-remote-sensing-1" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Discriminate green macrophytes using remote sensing</h2>
<h3 id="conclusion">Conclusion</h3>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1</span> 2 <span style="opacity:0.25">3 4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">7</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 30%; left: 0%; ">
<p><img data-src="Images/BedePaperCover.png" height="500"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="1" style="font-size: 35px; line-height: 1.3; margin: 10px; padding: 40px; text-align: justify-all;top: 12%; left: 53%; ">
<ul>
<li class="fragment"><span style="font-size: 60px">Key points:</span>
<ul>
<li class="fragment">The study assessed the ability to <span style="color: red">distinguish between five different vegetative intertidal habitats</span> by analyzing their spectral reflectance signatures.</li>
<li class="fragment">Around 366 spectra were compiled along the European Atlantic coast, from Southern Spain to Northern France.</li>
<li class="fragment">The spectral library was analyzed at <span style="color: red">various multi- and hyperspectral resolutions</span>, comparing satellite and drone sensors.</li>
<li class="fragment">The analysis highlighted the effectiveness of a random forest spectral classification model in <span style="color: red">differentiating between differently pigmented habitats and even between similarly pigmented classes</span>.</li>
<li class="fragment">High accuracy in distinguishing vegetation was found for hyperspectral sensors and multispectral sensors with more than <span style="color: red">eight bands in the visible and near-infrared</span>.</li>
<li class="fragment">The study <span style="color: red">provides insights for the next generation of satellite missions</span> regarding optimal spectral resolution and important wavelengths for effective monitoring of intertidal ecosystems.</li>
</ul></li>
</ul>
</div>
</section>
<section id="drone-mapping-sites-presentation" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Sites Presentation</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">8</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 7%; left: 20%; ">
<p><img data-src="Images/Fig1_Map_Drone_Sites.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 7%; left: 15%; ">
<p><img data-src="Images/Table_Flights.png" height="1000"></p>
</div>
<div class="fragment fade-in" data-fragment-index="3">
<div class="redbox absolute" style="top: 17.3%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="redbox absolute" style="top: 30.8%; left: 48%; width: 750px; height: 40px; ">

</div>
<div class="redbox absolute" style="top: 57%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="redbox absolute" style="top: 87%; left: 30%; width: 40px; height: 40px; ">

</div>
<div class="absolute" style="top: 85%; left: 33%; ">
<p><span style="font-size: 35px">Training Flights</span></p>
</div>
</div>
<div class="fragment fade-in" data-fragment-index="3">
<div class="greenbox absolute" style="top: 23.7%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 37%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 43.5%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 50.1%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 63.8%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 70%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 77%; left: 48%; width: 750px; height: 45px; ">

</div>
<div class="greenbox absolute" style="top: 87%; left: 60%; width: 40px; height: 40px; ">

</div>
<div class="absolute" style="top: 85%; left: 63%; ">
<p><span style="font-size: 35px">Predicting Flights</span></p>
</div>
</div>
</section>
<section id="drone-mapping-drone-specs" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Drone Specs</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">9</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 7%; left: -5%; ">
<p><img data-src="Images/MatriceMicasenseDike.jpg" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 50%; left: -5%; ">
<p><img data-src="Images/MicasenseCamera.jpg" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 10%; right: 0%; ">
<p><img data-src="Images/MicasenseS2.png" height="1000"></p>
</div>
</section>
<section id="drone-mapping-workflow" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Workflow</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">10</span></p>
</div>
<div class="absolute" style="left: 15%; ">
<p><img data-src="Images/Flowchart_Simon.png" height="1030"></p>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="1">
<div class="redbox absolute" style="border: 10px solid;top: 20.3%; left: 18.5%; width: 1262px; height: 420px; ">

</div>
<div class="greenbox absolute" style="border: 10px solid;top: 60%; left: 18.5%; width: 1262px; height: 221px; ">

</div>
<div class="absolute" style="top: 14%; left: 55%; ">
<p><span style="color: red">12 m Flights</span></p>
</div>
<div class="absolute" style="top: 53%; left: 54%; ">
<p><span style="color: #0EA019">120 m Flights</span></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="2">
<div class="absolute" style="top: 85%; left: 15%; ">
<p><img data-src="Images/Arrow_right.png" height="80"></p>
</div>
<div class="absolute" style="top: 86%; left: 2%; ">
<p>Input Data</p>
</div>
<div class="absolute" style="top: 86%; left: 80%; ">
<p>Output</p>
</div>
</div>
<div class="redbox fragment fade-in-then-out absolute" data-fragment-index="3" style="border: 7px solid;top: 45.5%; left: 40%; width: 150px; height: 80px; ">

</div>
<div class="redbox fragment fade-in-then-out absolute" data-fragment-index="4" style="border: 7px solid;top: 25.5%; left: 28.8%; width: 185px; height: 80px; ">

</div>
<div class="fragment fade-in-then-out" data-fragment-index="5">
<div class="redbox absolute" style="border: 7px solid;top: 31%; left: 40%; width: 150px; height: 70px; ">

</div>
<div class="redbox absolute" style="border: 7px solid;top: 60.5%; left: 40%; width: 150px; height: 70px; ">

</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="6">
<div class="redbox absolute" style="border: 7px solid;top: 11%; left: 28.8%; width: 185px; height: 70px; ">

</div>
<div class="redbox absolute" style="border: 7px solid;top: 80.5%; left: 28.8%; width: 185px; height: 70px; ">

</div>
</div>
<div class="redbox fragment fade-in-then-out absolute" data-fragment-index="7" style="border: 7px solid;top: 45.5%; left: 73.5%; width: 185px; height: 80px; ">

</div>
<div class="redbox fragment fade-in-then-out absolute" data-fragment-index="8" style="border: 7px solid;top: 14.5%; left: 77.8%; width: 155px; height: 115px; ">

</div>
</section>
<section id="drone-mapping-classified-maps" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Classified maps</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">11</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="7">
<div class="absolute" style="left: 5%; ">
<p><img data-src="Images/Gaf_Low_RGB.png" height="1150"></p>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="1">
<div class="blackarrow absolute" style="border: 4px solid;top: 70%; left: 34%; width: 500px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 55%; ">
<p><img data-src="Images/Gaf_Low_Green_RGB.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 68.5%; ">
<p><strong>Chlorophyceae</strong></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="2">
<div class="blackarrow absolute" style="border: 4px solid;top: 55%; left: 27%; width: 700px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 55%; ">
<p><img data-src="Images/Gaf_Low_MPB_RGB.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 68.5%; ">
<p><strong>Microphytobenthos</strong></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="3">
<div class="blackarrow absolute" style="border: 4px solid;top: 28%; left: 28.5%; width: 700px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 55%; ">
<p><img data-src="Images/Gaf_Low_Magno_RGB.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 68.5%; ">
<p><strong>Magnoliopsida</strong></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="4">
<div class="blackarrow absolute" style="border: 4px solid;top: 33%; left: 35%; width: 700px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 55%; ">
<p><img data-src="Images/Gaf_Low_Red_RGB.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 68.5%; ">
<p><strong>Rodophyceae</strong></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="5">
<div class="blackarrow absolute" style="border: 4px solid;top: 80%; left: 35%; width: 700px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 55%; ">
<p><img data-src="Images/Gaf_Low_Xantho_RGB.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 68.5%; ">
<p><strong>Xanthophyceae</strong></p>
</div>
</div>
<div class="fragment fade-in" data-fragment-index="6">
<div class="absolute" style="left: 50%; ">
<p><img data-src="Images/Gaf_Low_Pred.png" height="1150"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="7">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_Green_RGB.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Gaf_Low_Green_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="11">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_MPB_RGB.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Gaf_Low_MPB_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="12">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_magno_RGB.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Gaf_Low_magno_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="13">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_red_RGB.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Gaf_Low_red_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="14">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_xantho_RGB.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Gaf_Low_xantho_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="18">
<div class="absolute fragment fade-in" data-id="BoatRGB" data-fragment-index="15" style="left: 0%; ">
<p><img data-src="Images/Boat_RGB.png" height="1000"></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="16">
<div class="blackarrow absolute" style="border: 4px solid;top: 45%; left: 33%; width: 900px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 65%; ">
<p><img data-src="Images/Boat_magno.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 71%; ">
<p><strong>Magnoliopsida</strong></p>
</div>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="17">
<div class="blackarrow absolute" style="border: 4px solid;top: 44%; left: 46%; width: 600px; height: 0px; ">

</div>
<div class="absolute" style="top: 20%; left: 65%; ">
<p><img data-src="Images/Boat_red.png" height="800"></p>
</div>
<div class="absolute" style="top: 82%; left: 71%; ">
<p><strong>Rodophyceae</strong></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="18" data-id="BoatRGB" style="top: 20%; left: -5%; ">
<p><img data-src="Images/Boat_RGB.png" height="600"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="18" style="top: 20%; right: 0%; ">
<p><img data-src="Images/Boat_pred.png" height="900"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="18" style="top: 22%; left: 45%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
<div class="fragment fade-in-then-out" data-fragment-index="19">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Boat_magno.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Boat_magno_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
<div class="fragment fade-in" data-fragment-index="20">
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/Boat_red.png" height="900"></p>
</div>
<div class="absolute" style="top: 10%; left: 45%; ">
<p><img data-src="Images/Boat_red_pred.png" height="900"></p>
</div>
<div class="absolute" style="top: 30%; right: 0%; ">
<p><img data-src="Images/Legend_Pred.png" height="300"></p>
</div>
</div>
</section>
<section id="drone-mapping-validation" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Validation</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">12</span></p>
</div>
<div class="absolute" data-id="ConfMatrix" style="top: 20%; left: 6%; ">
<p><img data-src="Images/ConfMatrix.png" height="700"></p>
</div>
<div class="absolute" style="top: 13%; left: 48%; ">
<p><strong>Truth</strong></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="1" style="left: 5%; bottom: 10%; ">
<p>Global Accuracy: <strong>0.95</strong></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="1" style="left: 35%; bottom: 10%; ">
<p>Kappa Coefficient: <strong>0.93</strong></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="1" style="left: 65%; bottom: 10%; ">
<p>Across <strong>10</strong> Drone Flights</p>
</div>
</section>
<section id="drone-mapping-validation-1" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Validation</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">12</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="1">
<div class="absolute" data-id="ConfMatrix" style="top: 25%; left: -5%; ">
<p><img data-src="Images/ConfMatrix.png" height="500"></p>
</div>
<div class="absolute" data-id="ConfMatrix" style="top: 22%; left: 60%; ">
<p><img data-src="Images/SensSpec.png" height="500"></p>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 5%; left: 20%; ">
<p><img data-src="Images/KappaVSGlobal.png" height="1200"></p>
</div>
</section>
<section id="drone-mapping-variable-importance" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: Variable Importance</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">14</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="3">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 15%; left: 0%; ">
<p><img data-src="Images/TableVIP1.png" height="400"></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="5">
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 15%; left: 0%; ">
<p><img data-src="Images/TableVIP1_1.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 55%; left: 0%; ">
<p><img data-src="Images/TableVIP2_1.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 25%; right: 3.3%; ">
<p>Accuracy = <span style="color: green"><strong>a</strong></span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 65%; right: 0%; ">
<p>Accuracy = <span style="color: green"><strong>a</strong></span> ± <span style="color: red"><strong>b</strong></span></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 10%; left: 20%; ">
<p><img data-src="Images/FigX_VIP1.png" height="1150"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 10%; left: 20%; ">
<p><img data-src="Images/FigX_VIP1_2.png" height="1150"></p>
</div>
</section>
<section id="drone-mapping-from-8-mm-to-80-mm" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Drone Mapping: From 8 mm to 80 mm</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2</span> 3 <span style="opacity:0.25">4 5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">15</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="3">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 5%; left: 0%; ">
<p><img data-src="Images/Gaf_Low_RGB.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 5%; left: 50%; ">
<p><img data-src="Images/GafHigh_RGB.png" height="1200"></p>
</div>
<div class="redbox fragment fade-in absolute" data-fragment-index="2" style="border: 7px solid;top: 43%; left: 74%; width: 10px; height: 10px; ">

</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="top: 18%; left: 15%; ">
<p><img data-src="Images/Bigpixelsize.png" height="800"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="4" style="top: 18%; left: 15%; ">
<p><img data-src="Images/Bothpixelsize.png" height="800"></p>
</div>
<div class="fragment fade-out" data-fragment-index="5">
<div class="fragment absolute fade-in" data-fragment-index="3" style="top: 20%; left: -3%; ">
<p><span style="color: red">120 m Flight</span></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="3" style="top: 30%; left: -3%; ">
<p><span style="color: red">80 mm pixel Size</span></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="4" style="top: 20%; left: 47%; ">
<p><span style="color: green">12 m Flight</span></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="4" style="top: 30%; left: 47%; ">
<p><span style="color: green">8 mm pixel Size</span></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 18%; left: 15%; ">
<p><img data-src="Images/MagnoRedGreen_small.png" height="800"></p>
</div>
<div class="fragment fade-out" data-fragment-index="8">
<div class="fragment absolute fade-in" data-fragment-index="5" style="top: 30%; left: 65%; ">
<ul>
<li>Magnoliopsida ?</li>
<li>Rodophyceae ?</li>
<li>Chlorophyceae ?</li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 18%; left: 15%; ">
<p><img data-src="Images/MagnoGreen_small.png" height="800"></p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="7" style="top: 60%; left: 65%; ">
<p>754689 80 mm pixels</p>
</div>
<div class="fragment absolute fade-in" data-fragment-index="7" style="top: 65%; left: 65%; ">
<ul>
<li>Class of the 80 mm pixels</li>
<li>Proportion of Class of the 8mm flight</li>
</ul>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="9">
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 5%; left: 10%; ">
<p><img data-src="Images/density_vs_proportion.png" height="1200"></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="10">
<div class="absolute fragment fade-in" data-fragment-index="9" style="top: 5%; left: 10%; ">
<p><img data-src="Images/density_vs_proportionFaded.png" height="1200"></p>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="9" style="top: 5%; left: 20%; ">
<p><img data-src="Images/density_vs_proportionRodo.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="10" style="top: 5%; left: 20%; ">
<p><img data-src="Images/density_vs_proportionRodo100.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="11" style="top: 5%; left: 20%; ">
<p><img data-src="Images/density_vs_proportionRodo50Rodo.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="12" style="top: 5%; left: 20%; ">
<p><img data-src="Images/density_vs_proportionRodo50Magno.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="13" style="top: 5%; left: 10%; ">
<p><img data-src="Images/density_vs_proportion.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="top: 30%; left: -5%; ">
<p><img data-src="Images/density_vs_proportionLegend.png" height="300"></p>
</div>
</section>
<section id="phenology-of-seagrass-using-sentinel-2" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Phenology of seagrass using Sentinel-2</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3</span> 4 <span style="opacity:0.25">5 6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">16</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 6%; left: 20%; ">
<p><img data-src="Images/Bedes_phenology/MapofPredictionSites.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="top: 12%; left: 0%; ">
<p><img data-src="Images/Bedes_phenology/MaxMinMaps_BourgneufPred.png" height="980"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="top: 25%; left: 20%; ">
<p><img data-src="Images/Zoffoli2020.png" height="500"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="4" style="top: 11%; left: 2%; ">
<p><img data-src="Images/Bedes_phenology/MaxMinMaps_Bourgneuf.png" height="980"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 5%; left: 12%; ">
<p><img data-src="Images/Bedes_phenology/PhenologyPlot2000DrawsGaussianccSpline.png" height="1250"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 20%; right: 0%; ">
<p><img data-src="Images/Bedes_phenology/PhenologyPlot2000DrawsGaussianccSpline_scale.png" height="500"></p>
</div>
</section>
<section id="bicome-project" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">BiCOME project</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4</span> 5 <span style="opacity:0.25">6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">17</span></p>
</div>
<div class="absolute" style="top: 10%; left: 0%; ">
<p><img data-src="Images/BiCOME_background.png" width="1200"></p>
</div>
<div class="absolute" style="top: 10%; left: 50%; ">
<p><img data-src="Images/PML_logo.png" width="500"></p>
</div>
<div class="absolute" style="top: 30%; left: 50%; ">
<p><img data-src="Images/UN_logo.png" width="450"></p>
</div>
<div class="absolute" style="top: 50%; left: 53%; ">
<p><img data-src="Images/DLR_logo.png" height="200"></p>
</div>
<div class="absolute" style="top: 77%; left: 51%; ">
<p><img data-src="Images/Hygeos_Logo.png" width="450"></p>
</div>
<div class="absolute" style="font-size: 40px;top: 47%; width: 1200px; ">
<ul>
<li>Identify and characterise critical applications (Pilot Studies) of remote sensing to study coastal biodiversity.</li>
</ul>
</div>
<div class="absolute" style="font-size: 40px;top: 55%; width: 1200px; ">
<ul>
<li>Evaluate existing and planned sensor capabilities for each Pilot Study.</li>
</ul>
</div>
<div class="absolute" style="font-size: 40px;top: 63%; width: 1200px; ">
<ul>
<li>Define the activities necessary to utilise current and planned sensors to detect measures of marine biodiversity; or define new approaches, if the existing ones are not considered capable to fulfil the targeted science objectives.</li>
</ul>
</div>
<div class="absolute" style="font-size: 40px;top: 11%; left: 75%; width: 400px; ">
<p>Project coordination and management and Pelagic case lead</p>
</div>
<div class="absolute" style="font-size: 40px;top: 32%; left: 75%; ">
<p>Intertidal lead</p>
</div>
<div class="absolute" style="font-size: 40px;top: 57%; left: 75%; ">
<p>Sub-tidal lead</p>
</div>
<div class="absolute" style="font-size: 40px;top: 81%; left: 75%; ">
<p>EO corrections lead</p>
</div>
</section>
<section id="additional-works-october-2022" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Additional Works: October 2022</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4</span> 5 <span style="opacity:0.25">6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">18</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="6">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 30%; left: -5%; ">
<p><img data-src="Images/Roman_et_al2023.png" height="400"></p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="2" style="top: 30%; left: 40%; ">
<p>Protential of Drone to identify oyster culture tables</p>
</div>
<div class="fragment fade-in absolute" data-fragment-index="3" style="top: 40%; left: 40%; ">
<ul>
<li>Identifing oyster table ?</li>
</ul>
</div>
<div class="fragment fade-in absolute" data-fragment-index="4" style="top: 50%; left: 40%; ">
<ul>
<li>Identifing mesh bag size ?</li>
</ul>
</div>
<div class="fragment fade-in absolute" data-fragment-index="5" style="top: 60%; left: 40%; ">
<ul>
<li>Identifing table height ?</li>
</ul>
</div>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="6" style="top: 5%; left: 15%; ">
<p><img data-src="Images/Roman_SiteFigure.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="7" style="top: 5%; left: 5%; ">
<p><img data-src="Images/Roman_Meshbags.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="8" style="top: 5%; left: 5%; ">
<p><img data-src="Images/Roman_Meshbagmaps.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="9" style="top: 5%; left: 15%; ">
<p><img data-src="Images/Roman_Height.png" height="1200"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="10" style="top: 20%; left: 0%; ">
<p><img data-src="Images/AlexSimonOyster.jpeg" height="700"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="10" style="top: 15%; left: 50%; ">
<p><img data-src="Images/MeshBagPicture.jpeg" height="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="11" style="top: 15%; right: 0%; ">
<p><img data-src="Images/P4D_vs_Metashape.png" height="900"></p>
</div>
</section>
<section id="additional-works-december-2022" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Additional Works: December 2022</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4</span> 5 <span style="opacity:0.25">6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">19</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="3">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 15%; left: 5%; ">
<p><img data-src="Images/Hasanuddin.jpeg" height="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 15%; left: 45%; ">
<p><img data-src="Images/SimonAgus.jpeg" height="1000"></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="5">
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 15%; left: -5%; ">
<p><img data-src="Images/Kapaphycus.jpeg" height="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 15%; right: 0%; ">
<p><img data-src="Images/AlgaeFarm.jpeg" height="1000"></p>
</div>
</div>
<div class="fragment fade-out" data-fragment-index="6">
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 15%; left: 0%; ">
<p><img data-src="Images/SimonWorkshop.jpeg" height="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 15%; right: 0%; ">
<p><img data-src="Images/SimonWorkshop2.jpeg" height="1000"></p>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 15%; right: 0%; ">
<p><img data-src="Images/PaperNurdin.png" height="1000"></p>
</div>
</section>
<section id="additional-works-march-2023" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Additional Works: March 2023</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4</span> 5 <span style="opacity:0.25">6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">20</span></p>
</div>
<div class="fragment fade-out" data-fragment-index="3">
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 5%; left: 10%; ">
<p><video data-src="Videos/Guadalquivir.MP4" height="1200" controls=""><a href="Videos/Guadalquivir.MP4">Video</a></video></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="bottom: 5%; right: 5%; ">
<p><img data-src="Images/GroupCadiz.jpg" height="500"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 20%; left: -5%; ">
<p><img data-src="Images/ICMAN_logo.png" height="155"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 40%; left: -5%; ">
<p><img data-src="Images/UN_logo.png" height="95"></p>
</div>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 5%; left: 0%; ">
<p><img data-src="Images/DroneGuadal.jpeg" height="600"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 50%; left: 10%; ">
<p><img data-src="Images/MPBsampling.jpg" height="600"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 5%; left: 65%; ">
<p><video data-src="Videos/MPBsampling.MOV" height="1250" controls=""><a href="Videos/MPBsampling.MOV">Video</a></video></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 5%; left: 32%; ">
<p><img data-src="Images/MicasenseCamera.jpeg" height="600"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 5%; left: 32.5%; ">
<p><img data-src="Images/Guadalquivir_MPB_site1.png" height="600"></p>
</div>
</section>
<section id="lectures-and-praticals" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Lectures and Praticals</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4</span> 5 <span style="opacity:0.25">6</span></p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">21</span></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="1" style="top: 25%; right: 50%; ">
<p><img data-src="Images/StudentOntheField.jpg" height="600"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="2" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
<li>Fieldwork with Master 2 students in Bourgneuf Bay : 1 day</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="3" style="top: 40%; right: 50%; ">
<p><img data-src="Images/FieldtripACES.jpg" height="600"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="4" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
<li>Fieldwork with Master 2 students in Bourgneuf Bay : 1 day</li>
</ul></li>
<li>December 2022:
<ul>
<li>Workshop in Indonesia, Introduction to remote Sensing : 2 days</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="4" style="top: 40%; right: 0%; ">
<p><img data-src="Images/SimonWorkshop2.jpeg" height="600"></p>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="5" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
<li>Fieldwork with Master 2 students in Bourgneuf Bay : 1 day</li>
</ul></li>
<li>December 2022:
<ul>
<li>Workshop in Indonesia, Introduction to remote Sensing : 2 days</li>
</ul></li>
<li>March 2023:
<ul>
<li>Lecture in quantitative ecology to 3rd year students: 1.5h</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="6" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
<li>Fieldwork with Master 2 students in Bourgneuf Bay : 1 day</li>
</ul></li>
<li>December 2022:
<ul>
<li>Workshop in Indonesia, Introduction to remote Sensing : 2 days</li>
</ul></li>
<li>March 2023:
<ul>
<li>Lecture in quantitative ecology to 3rd year students: 1.5h</li>
</ul></li>
<li>April to may 2023:
<ul>
<li>Praticals in quantitative ecology to 3rd year students: 24h</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in-then-out" data-fragment-index="7" style="top: 5%; left: 0%; ">
<ul>
<li>September 2022:
<ul>
<li>Fieldwork with Master 2 students in the Gulf of Morbihan : 1 day</li>
<li>Introduction to remote Sensing to Master 2 students: 8h</li>
<li>Fieldwork with Master 2 students in Bourgneuf Bay : 1 day</li>
</ul></li>
<li>December 2022:
<ul>
<li>Workshop in Indonesia, Introduction to remote Sensing : 2 days</li>
</ul></li>
<li>March 2023:
<ul>
<li>Lecture in quantitative ecology to 3rd year students: 1.5h</li>
</ul></li>
<li>April to may 2023:
<ul>
<li>Praticals in quantitative ecology to 3rd year students: 24h</li>
<li>Fieldwork Pratical with 3rd year students: 3 days</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 40%; right: 0%; ">
<p><video data-src="Videos/DJI_0076_1.mp4" height="400" controls=""><a href="Videos/DJI_0076_1.mp4">Video</a></video></p>
</div>
</section>
<section id="conclusion-whats-coming-next" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Conclusion: What’s coming next ?</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4 5</span> 6</p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">22</span></p>
</div>
<div class="fragment fade-in" data-fragment-index="1">
<ul>
<li>Publication:
<ul>
<li>Write a paper about green macrophytes discrimination using Drone
<ul>
<li>Remote Sensing of Environment</li>
</ul></li>
</ul></li>
</ul>
</div>
<div class="fragment fade-in" data-fragment-index="2">
<ul>
<li>Congress:
<ul>
<li>European Phycological Congress</li>
</ul></li>
</ul>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 50%; right: 0%; ">
<p><img data-src="Images/EPC8.png" height="600"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 6%; left: 0%; ">
<p><img data-src="Images/EPC8Evan.png" height="400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 6%; right: 0%; ">
<p><img data-src="Images/EPC8Oiry.png" height="400"></p>
</div>
</section>
<section id="conclusion-workflow-of-the-thesis" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Conclusion: Workflow of the thesis</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4 5</span> 6</p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">23</span></p>
</div>
<div class="absolute fragment fade-out" data-fragment-index="1" style="top: 11%; left: 0%; ">
<p><img data-src="Images/workflowthesis_3.png" width="2400"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 11%; left: 0%; ">
<p><img data-src="Images/workflowthesis_final.png" width="2400"></p>
</div>
</section>
<section id="conclusion-list-of-paper-published-since-january-2022" class="slide level2" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">Conclusion: List of paper published since January 2022</h2>
<div class="absolute" style="top: 0px; left: 95%; ">
<div class="sectionhead">
<p><span style="opacity:0.25">1 2 3 4 5</span> 6</p>
</div>
</div>
<div class="absolute" style="bottom: 0%; right: -2%; ">
<p><span style="color: black;">23</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 5%; left: 0%; ">
<p><img data-src="Images/Paper/Brunier1.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="2" style="top: 25%; left: 0%; ">
<p><img data-src="Images/Paper/Brunier2.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="3" style="top: 47%; left: 0%; ">
<p><img data-src="Images/Paper/Zoffoli.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 72%; left: 0%; ">
<p><img data-src="Images/Paper/Bede1.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="1" style="top: 40%; left: -5%; ">
<p><img data-src="Images/published.png" width="50"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="4" style="top: 72%; left: 0%; ">
<p><img data-src="Images/Paper/Bede1.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 10%; right: 10%; ">
<p><img data-src="Images/Paper/Nurdin.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="6" style="top: 35%; right: 10%; ">
<p><img data-src="Images/Paper/Roman_et_al2023.png" width="1000"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="5" style="top: 20%; right: 5%; ">
<p><img data-src="Images/submitted.png" width="50"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="top: 60%; right: 5%; ">
<p><img data-src="Images/coming_soon.png" width="50"></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="7" style="font-size: 40px; line-height: 1;top: 60%; bottom: 0%; right: 6%; width: 1100px; ">
<ul>
<li>Drone mapping of intertidal soft bottom vegetation across 10 study sites and 2 countries</li>
</ul>
<p><span style="font-size: 25px;">Simon Oiry, Bede Ffinian Rowe Davies, Ana Sousa, Philippe Rosa, Pierre Gernez, Laurent Barillé</span></p>
</div>
<div class="absolute fragment fade-in" data-fragment-index="8" style="font-size: 40px; line-height: 1;top: 80%; bottom: 0%; right: 6%; width: 1100px; ">
<ul>
<li>Spatio-temporal variability of intertidal seagrass meadow across a 23° latitudinal gradient: a study of 12 sites</li>
</ul>
<p><span style="font-size: 25px;">Bede Ffinian Rowe Davies, Simon Oiry, Ana Sousa, Philippe Rosa, Pierre Gernez, Laurent Barillé …</span></p>
</div>
</section>
<section id="the-end" class="slide level2" data-background-image="Images/Slide1_Background.png" data-auto-animate="true" style="font-size: 60px;">
<h2 data-id="quarto-animate-title">The End</h2>
<div class="absolute" style="top: 23%; left: 27%; width: 1000px; ">
<p><span style="font-size: 200px; color: black">Thanks you for listening</span></p>
</div>

<img src="Images/nantes-universite.png" class="slide-logo r-stretch"><div class="footer footer-default">
<p>Simon Oiry, Follow-up Committee Meeting 2023</p>
</div>
</section>
    </div>
  </div>

  <script>window.backupDefine = window.define; window.define = undefined;</script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/dist/reveal.js"></script>
  <!-- reveal.js plugins -->
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/quarto-line-highlight/line-highlight.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/pdf-export/pdfexport.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/reveal-menu/menu.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/reveal-menu/quarto-menu.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/quarto-support/support.js"></script>
  

  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/notes/notes.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/search/search.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/zoom/zoom.js"></script>
  <script src="Slides_CSI_2023_2_files/libs/revealjs/plugin/math/math.js"></script>
  <script>window.define = window.backupDefine; window.backupDefine = undefined;</script>

  <script>

      // Full list of configuration options available at:
      // https://revealjs.com/config/
      Reveal.initialize({
'controlsAuto': true,
'previewLinksAuto': false,
'smaller': false,
'pdfSeparateFragments': false,
'autoAnimateEasing': "ease",
'autoAnimateDuration': 1,
'autoAnimateUnmatched': true,
'menu': {"side":"left","useTextContentForMissingTitles":true,"markers":false,"loadIcons":false,"custom":[{"title":"Tools","icon":"<i class=\"fas fa-gear\"></i>","content":"<ul class=\"slide-menu-items\">\n<li class=\"slide-tool-item active\" data-item=\"0\"><a href=\"#\" onclick=\"RevealMenuToolHandlers.fullscreen(event)\"><kbd>f</kbd> Fullscreen</a></li>\n<li class=\"slide-tool-item\" data-item=\"1\"><a href=\"#\" onclick=\"RevealMenuToolHandlers.speakerMode(event)\"><kbd>s</kbd> Speaker View</a></li>\n<li class=\"slide-tool-item\" data-item=\"2\"><a href=\"#\" onclick=\"RevealMenuToolHandlers.overview(event)\"><kbd>o</kbd> Slide Overview</a></li>\n<li class=\"slide-tool-item\" data-item=\"3\"><a href=\"#\" onclick=\"RevealMenuToolHandlers.overview(event)\"><kbd>e</kbd> PDF Export Mode</a></li>\n<li class=\"slide-tool-item\" data-item=\"4\"><a href=\"#\" onclick=\"RevealMenuToolHandlers.keyboardHelp(event)\"><kbd>?</kbd> Keyboard Help</a></li>\n</ul>"}],"openButton":true},
'smaller': false,
 
        // Display controls in the bottom right corner
        controls: false,

        // Help the user learn the controls by providing hints, for example by
        // bouncing the down arrow when they first encounter a vertical slide
        controlsTutorial: false,

        // Determines where controls appear, "edges" or "bottom-right"
        controlsLayout: 'edges',

        // Visibility rule for backwards navigation arrows; "faded", "hidden"
        // or "visible"
        controlsBackArrows: 'faded',

        // Display a presentation progress bar
        progress: true,

        // Display the page number of the current slide
        slideNumber: false,

        // 'all', 'print', or 'speaker'
        showSlideNumber: 'all',

        // Add the current slide number to the URL hash so that reloading the
        // page/copying the URL will return you to the same slide
        hash: true,

        // Start with 1 for the hash rather than 0
        hashOneBasedIndex: false,

        // Flags if we should monitor the hash and change slides accordingly
        respondToHashChanges: true,

        // Push each slide change to the browser history
        history: true,

        // Enable keyboard shortcuts for navigation
        keyboard: true,

        // Enable the slide overview mode
        overview: true,

        // Disables the default reveal.js slide layout (scaling and centering)
        // so that you can use custom CSS layout
        disableLayout: false,

        // Vertical centering of slides
        center: false,

        // Enables touch navigation on devices with touch input
        touch: true,

        // Loop the presentation
        loop: false,

        // Change the presentation direction to be RTL
        rtl: false,

        // see https://revealjs.com/vertical-slides/#navigation-mode
        navigationMode: 'linear',

        // Randomizes the order of slides each time the presentation loads
        shuffle: false,

        // Turns fragments on and off globally
        fragments: true,

        // Flags whether to include the current fragment in the URL,
        // so that reloading brings you to the same fragment position
        fragmentInURL: false,

        // Flags if the presentation is running in an embedded mode,
        // i.e. contained within a limited portion of the screen
        embedded: false,

        // Flags if we should show a help overlay when the questionmark
        // key is pressed
        help: true,

        // Flags if it should be possible to pause the presentation (blackout)
        pause: true,

        // Flags if speaker notes should be visible to all viewers
        showNotes: false,

        // Global override for autoplaying embedded media (null/true/false)
        autoPlayMedia: true,

        // Global override for preloading lazy-loaded iframes (null/true/false)
        preloadIframes: null,

        // Number of milliseconds between automatically proceeding to the
        // next slide, disabled when set to 0, this value can be overwritten
        // by using a data-autoslide attribute on your slides
        autoSlide: 0,

        // Stop auto-sliding after user input
        autoSlideStoppable: true,

        // Use this method for navigation when auto-sliding
        autoSlideMethod: null,

        // Specify the average time in seconds that you think you will spend
        // presenting each slide. This is used to show a pacing timer in the
        // speaker view
        defaultTiming: null,

        // Enable slide navigation via mouse wheel
        mouseWheel: false,

        // The display mode that will be used to show slides
        display: 'block',

        // Hide cursor if inactive
        hideInactiveCursor: true,

        // Time before the cursor is hidden (in ms)
        hideCursorTime: 5000,

        // Opens links in an iframe preview overlay
        previewLinks: false,

        // Transition style (none/fade/slide/convex/concave/zoom)
        transition: 'fade',

        // Transition speed (default/fast/slow)
        transitionSpeed: 'default',

        // Transition style for full page slide backgrounds
        // (none/fade/slide/convex/concave/zoom)
        backgroundTransition: 'none',

        // Number of slides away from the current that are visible
        viewDistance: 3,

        // Number of slides away from the current that are visible on mobile
        // devices. It is advisable to set this to a lower number than
        // viewDistance in order to save resources.
        mobileViewDistance: 2,

        // The "normal" size of the presentation, aspect ratio will be preserved
        // when the presentation is scaled to fit different resolutions. Can be
        // specified using percentage units.
        width: 2400,

        height: 1350,

        // Factor of the display size that should remain empty around the content
        margin: 0.1,

        math: {
          mathjax: 'https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js',
          config: 'TeX-AMS_HTML-full',
          tex2jax: {
            inlineMath: [['\\(','\\)']],
            displayMath: [['\\[','\\]']],
            balanceBraces: true,
            processEscapes: false,
            processRefs: true,
            processEnvironments: true,
            preview: 'TeX',
            skipTags: ['script','noscript','style','textarea','pre','code'],
            ignoreClass: 'tex2jax_ignore',
            processClass: 'tex2jax_process'
          },
        },

        // reveal.js plugins
        plugins: [QuartoLineHighlight, PdfExport, RevealMenu, QuartoSupport,

          RevealMath,
          RevealNotes,
          RevealSearch,
          RevealZoom
        ]
      });
    </script>
    <script id="quarto-html-after-body" type="application/javascript">
    window.document.addEventListener("DOMContentLoaded", function (event) {
      const toggleBodyColorMode = (bsSheetEl) => {
        const mode = bsSheetEl.getAttribute("data-mode");
        const bodyEl = window.document.querySelector("body");
        if (mode === "dark") {
          bodyEl.classList.add("quarto-dark");
          bodyEl.classList.remove("quarto-light");
        } else {
          bodyEl.classList.add("quarto-light");
          bodyEl.classList.remove("quarto-dark");
        }
      }
      const toggleBodyColorPrimary = () => {
        const bsSheetEl = window.document.querySelector("link#quarto-bootstrap");
        if (bsSheetEl) {
          toggleBodyColorMode(bsSheetEl);
        }
      }
      toggleBodyColorPrimary();  
      const tabsets =  window.document.querySelectorAll(".panel-tabset-tabby")
      tabsets.forEach(function(tabset) {
        const tabby = new Tabby('#' + tabset.id);
      });
      const clipboard = new window.ClipboardJS('.code-copy-button', {
        target: function(trigger) {
          return trigger.previousElementSibling;
        }
      });
      clipboard.on('success', function(e) {
        // button target
        const button = e.trigger;
        // don't keep focus
        button.blur();
        // flash "checked"
        button.classList.add('code-copy-button-checked');
        var currentTitle = button.getAttribute("title");
        button.setAttribute("title", "Copied!");
        let tooltip;
        if (window.bootstrap) {
          button.setAttribute("data-bs-toggle", "tooltip");
          button.setAttribute("data-bs-placement", "left");
          button.setAttribute("data-bs-title", "Copied!");
          tooltip = new bootstrap.Tooltip(button, 
            { trigger: "manual", 
              customClass: "code-copy-button-tooltip",
              offset: [0, -8]});
          tooltip.show();    
        }
        setTimeout(function() {
          if (tooltip) {
            tooltip.hide();
            button.removeAttribute("data-bs-title");
            button.removeAttribute("data-bs-toggle");
            button.removeAttribute("data-bs-placement");
          }
          button.setAttribute("title", currentTitle);
          button.classList.remove('code-copy-button-checked');
        }, 1000);
        // clear code selection
        e.clearSelection();
      });
      function tippyHover(el, contentFn) {
        const config = {
          allowHTML: true,
          content: contentFn,
          maxWidth: 500,
          delay: 100,
          arrow: false,
          appendTo: function(el) {
              return el.closest('section.slide') || el.parentElement;
          },
          interactive: true,
          interactiveBorder: 10,
          theme: 'quarto-reveal',
          placement: 'bottom-start'
        };
          config['offset'] = [0,0];
          config['maxWidth'] = 700;
        window.tippy(el, config); 
      }
      const noterefs = window.document.querySelectorAll('a[role="doc-noteref"]');
      for (var i=0; i<noterefs.length; i++) {
        const ref = noterefs[i];
        tippyHover(ref, function() {
          // use id or data attribute instead here
          let href = ref.getAttribute('data-footnote-href') || ref.getAttribute('href');
          try { href = new URL(href).hash; } catch {}
          const id = href.replace(/^#\/?/, "");
          const note = window.document.getElementById(id);
          return note.innerHTML;
        });
      }
      const findCites = (el) => {
        const parentEl = el.parentElement;
        if (parentEl) {
          const cites = parentEl.dataset.cites;
          if (cites) {
            return {
              el,
              cites: cites.split(' ')
            };
          } else {
            return findCites(el.parentElement)
          }
        } else {
          return undefined;
        }
      };
      var bibliorefs = window.document.querySelectorAll('a[role="doc-biblioref"]');
      for (var i=0; i<bibliorefs.length; i++) {
        const ref = bibliorefs[i];
        const citeInfo = findCites(ref);
        if (citeInfo) {
          tippyHover(citeInfo.el, function() {
            var popup = window.document.createElement('div');
            citeInfo.cites.forEach(function(cite) {
              var citeDiv = window.document.createElement('div');
              citeDiv.classList.add('hanging-indent');
              citeDiv.classList.add('csl-entry');
              var biblioDiv = window.document.getElementById('ref-' + cite);
              if (biblioDiv) {
                citeDiv.innerHTML = biblioDiv.innerHTML;
              }
              popup.appendChild(citeDiv);
            });
            return popup.innerHTML;
          });
        }
      }
    });
    </script>
    

</body></html>
