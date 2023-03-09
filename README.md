# Reversible-Datahiding-in-Encrypted-Images

This paper proposes a scheme of data hiding in encrypted images. It's project done during 3rd year of my B.Tech program.

In the encryption phase, the original data is encrypted into images by using the stream cypher. Then the additional data is embedded into the image by modifying a small portion of encrypted data. 

It is based on the pixel redundancy within each block. As the majority of the encrypted image is kept unchanged, the quality of the decrypted image is acceptable.

In the receiver phase, the image is successfully extracted from the encrypted image with the help of an encryption key. The receiver can further recover the original plaintext image without any error by using the data hiding key. 

With an encrypted image containing additional data, one may first decrypt it using the encryption key and the decryption version is similar to the original image. Then by using the data hiding key, user can recover the original data without loss. 

According to the data hiding key, with the help of spatial correlation in a natural image, the embedded data can be successfully extracted and the original image can be perfectly recovered without loss.
