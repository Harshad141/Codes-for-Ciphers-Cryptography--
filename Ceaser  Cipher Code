//The following code in JavaScript to convert Plain Txt to Cipher Txt using CEASER CIPHER

CODE:-
 let ceaserCipher = (str) =>{
  let decoded =                           //Letter Refference
  {
    a: 'n', b: 'o', c: 'p',
    d: 'q', e: 'r', f: 's',
    g: 't', h: 'u', i: 'v',
    j: 'w', k: 'x', l: 'y',
    m: 'z', n: 'a', o: 'b',
    p: 'c', q: 'd', r: 'e',
    s: 'f', t: 'g', u: 'h',
    v: 'i', w: 'j', x: 'k',
    y: 'l', z: 'm'    
  }
   str = str.toLowerCase();              //convert the string to lowercase
   let decipher = '';                    //decipher the code
  for(let i = 0 ; i < str.length; i++){
    decipher += decoded[str[i]];
  }
    return decipher;                     //return the output
}



Input:
console.log(ceaserCipher('attackatonce'));
console.log(ceaserCipher('prashantyadav'));

Output:
"nggnpxngbapr"
"cenfunaglnqni"
