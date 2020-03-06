# Tidbits
Random compilation of javascript tips

## Promises
Can only **await** in For of/ For in/ For/ While loops but not higher order array functions/ loops that use a callback  
  * Array.map will return an array of pending promises in this situation.  
  * Will require a Promise.all(promisesArray) to resolve all the promises.  
