if (config.runsInWidget) {
  const widget = new ListWidget();

let doneDate = new Date(2021,4,27)
let nowdays = new Date()

  let days = (doneDate - nowdays)/ (1000 * 60 * 60 * 24)  
  let res = Math.floor(days)
  const text = widget.addText("距离系分考试还有");
  text.textColor = new Color('#000000')
  text.font = Font.boldSystemFont(24)
  text.centerAlignText();
  
  const num = widget.addText(""+res);
  num.textColor = new Color('#E3193B')
  num.font = Font.boldSystemFont(32)
  num.centerAlignText();

  
  const last = widget.addText("天！");
  last.textColor = new Color('#000000')
  last.font = Font.boldSystemFont(24)
  last.centerAlignText();
  

  const gradient = new LinearGradient();
  gradient.locations = [0, 1]
  gradient.colors = [new Color("#48D3AC"), new Color('#f3b626')]
  widget.backgroundGradient = gradient;
  Script.setWidget(widget);
}else{
log("message")
}
