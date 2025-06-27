HTML Smuggling example 

Modified PoC by Sofiane Hamlaoui with my inert payload
  https://github.com/SofianeHamlaoui/Pentest-Notes/blob/master/offensive-security/defense-evasion/file-smuggling-with-html-and-javascript.md

Options

  1.  eicar-simple
      Browse to https://paulsery.github.io/htmlSmuggling/eicar-simple.html
  
  2.  helloworld C executable
      Compile payload:
      gcc -o helloworld helloworld.c

      Encode executable as base64
      base64 helloworld > helloworld.b64

      Browse to https://paulsery.github.io/htmlSmuggling/helloworld.exe to download the payload

  3.  helloworld text
      ...
      Browse to https://paulsery.github.io/htmlSmuggling/helloworld.html to download the text file
