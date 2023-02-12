```
function downloadBlob(blobURL){
  const link = document.createElement('a');
  link.href = blobURL;
  link.download = 'download';
  link.click();
}
```
