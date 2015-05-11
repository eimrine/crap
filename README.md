# crap

var ar1 = [1, 5, 6, 4, 3, 5, 100, -20];
  function funDo(ar){
  for(k=0,i=1,temp = ar.length-1;k<temp;k++)i=(i<<
1)+1;
  for(;i>0;i--){
  for(k=0,sum=0,temp2=[];k<ar.length;k++)
  if((i>>(k))%2) { sum+=ar[k]; temp2.push(ar[k]);}
  if(sum==10) console.log(temp2);}
  }
  funDo(ar1);
