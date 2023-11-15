### Approach used
We will just modify the same code we used in basic-mod1 by again using nano editor and this time using the new sequence '268 413 438 313 426 337 272 188 392 338 77 332 139 113 92 239 247 120 419 72 295 190 131' and also changing ` flag += alphabet[int(i) % 37]` to `flag += alphabet[pow(int(i), -1, 41) - 1]`.

![image](https://github.com/UselessAaka/picoCTF-Writeups/assets/148384618/2a90c0e5-2b81-4532-9035-fb5bc1f5bea2)

and after saving we will run the code using python3 and get the flag.

![image](https://github.com/UselessAaka/picoCTF-Writeups/assets/148384618/824ab214-c87c-48c3-8bd4-8a19c258bcd1)

### Flag 
> picoCTF{1nv3r53ly_h4rd_8a05d939}

### Resources used 
To edit the code I referred to [this video.](https://www.youtube.com/watch?v=L18kp5QXhEk)
