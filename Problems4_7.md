# Problems4_7

DES算法遵守Feistel密码结构，因此有<br/>
Ri+1=Li<br/>
Li+1=Li⊕F(Ri,Ki)<br/>
解密过程中将Ri+1,Li+1代入上述式得：<br/>
Li+1=Ri<br/>
Li+1⊕F(Ri,Ki)=Li⊕F(Ri,Ki)⊕F(Li+1,Ki)=Li⊕F(Ri,Ki)⊕F(Ri,Ki)=Li<br/>
代入后左右两边得到的结果是加密过程之中的上一轮的左右部分<br/>
DES算法的解密算法与加密算法相同，只是各子密钥的顺相反，即为K16，K15，…，K1<br/>
因此DES的解密算法是加密算法的逆运算
