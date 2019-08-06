# removeduplicants
<html>
<body>
<script>
  var str="abbbcdefqqrsssstop";
  var index=0;
    for(var i=0;i<str.length;i++)
   { 
     for{var j=0;j<i;j++)
      { 
        if(str[i]==str[j])
        {    break;}
        if(j==i)
        { str[index++]=str[i]}
  }
   documents.write(str);    
</script>

</body>
</html>
