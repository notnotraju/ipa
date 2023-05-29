# ipa
This repo contains an implementation of a polynomial commitment scheme based on the inner product argument, closely following https://eprint.iacr.org/2019/1021.pdf and https://vitalik.ca/general/2021/11/05/halo.html. The implementation is designed such that the verifier is _circuit friendly_, in the sense that one may write a simple Halo2 circuit doing the verifier computation.

