function sumvoy(ch)
{ 
  
  voy[0]= a;
  voy[1]= e;
  voy[2]= y;
  voy[3]= u;
  voy[4]= i;
  voy[5]= o;
  let n=length(ch);
  
    
    if (length(ch) = '.' )
    { 
    let sum = 0;
    let sumv= 0;
    for (let i=0; i<n; i++)
    {
         for (let j=0; i<5; i++)
         {
            if (ch[i] = voy[j])
            {
          sumv = sumv + 1;
            sum = sum +1 ;
            }
        
        else { sum = sum + 1 }
         }
    }
 
    return sum;
    return sumv;
    } 
}
function sumdist(set,set1) 
{
  let tem=false;
  let s=0;
  for (i=0;i<5;i++)
  {

    for (j=0;j<5;i++)
      { if (set[i]=set1[j]) 
        { tem=true;
          break ;
        
        }
      if (tem=true)  
      {
        s=s+set[i];
      }
      } 
   }
return s;







}

<!---
Zaydounn/Zaydounn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
