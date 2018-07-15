# dragvisuals
Plugin for dragging visual blocks by Damian Conway. Have a look at his [YouTube presentation](https://www.youtube.com/watch?v=aHm36-na4-4).

You can drag and duplicate visual blocks using this plugin, which is useful at times and is better than copying and pasting.
The mappings are--

    vmap <expr> <S-LEFT>  DVB_Drag('left')
    vmap <expr> <S-RIGHT> DVB_Drag('right')
    vmap <expr> <S-DOWN>  DVB_Drag('down')
    vmap <expr> <S-UP>    DVB_Drag('up')
    vmap <expr> D         DVB_Duplicate()

You can, of course, change this mappings at your will.
