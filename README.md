# text lenght function 
function truncateText(text: string,value:number) {
    if (text.length <= value) {
      return text;
    } else {
      return text.slice(0, value) + "..";
    }
  }

  /////////////////////////////
