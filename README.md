# myblsmiraclproject
完成bls签名rfc草案中(https://www.ietf.org/archive/id/draft-irtf-cfrg-bls-signature-05.html)有,mcore中没有实现的部分

说明：
1. 可以直接解压mcore.zip至mcore.zip所在目录，也可以自行从https://github.com/miracl/core/tree/master/rust 按文档说明获取，然后放到笨项目根目录下；
2. mcore/src/bls12381/bls.rs文件中已有hash_to_field,bls_hash_to_point,key_pair_generate,core_sign,core_verify的实现；
3. 对照bls草案规范，可在mcore的基础上完成Aggreate(2.8),CoreAggregratgeVerify(2.9)，以及BLS消息签名(3.)，密码套件(4.)等其他部分
