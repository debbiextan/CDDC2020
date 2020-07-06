**[Pwn (Linux)-2] (2ˆ31)-1**

Given: zer0.chall.cddc2020.nshc.sg 20002

Solution:
1. Netcat into given port, input of postive number requested - this shows that it is likely that integer overflow attack is required
2. Input representation of (2ˆ31)-1 = 2147483647  
  Output: 2147483647 
3. Input representation of (2ˆ32)-1 = 4294967295  
 Output: -1
4. Overflow with input 4294967296 (+1 from representation of 2ˆ31-1)  
 Output: *flag*

Flag: CDDC20{oO0OoO0o0OoO0Oo}
