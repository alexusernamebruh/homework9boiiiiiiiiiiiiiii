# homework9boiiiiiiiiiiiiiii
const homework9e=(champion)=>
  champion.data.Aatrox.spells.map((e)=>({
     tooltip:e.tooltip,
    rangeBurn:e.rangeBurn,
      imageName:e.image.full,
    costType:e.costType,
}));
