# rework
## Why are those ports in this collection ?
#### For some reasons, the port can not be compiled fully automatically with the 'enter-nutyx' script. As this script is trying to compile every ports per level include in a collection. The broken ports have to be remove until it's fixed when possible.

### They can be 3 reasons

   1. The port have a compilation failure
   2. The port have files in conflits with other files port
   3. The port needs dependencies thats are not in any existing collection
   
### reason 1:
It's quite clear, the port rezept need to be review and adapt to the current version of NuTyX.
### reason 2: 
Is normaly very easy to fixe. Remove the files in conflits.
### reason 3:
It cannot be integrated in the standard collection because of the full automated process
