# awesome-theoretical-cryptoeconomics
This is a collection of theoretical cryptography research papers where the adversary is both computationally bounded and economically bounded

Specifically, this is a collection of theoretical crypto where the model includes the option to economically punish bad-acting players. This could be in the form of "slashing" (i.e. giving a "fine" -- we assume everyone put a deposit ahead of time). Or it can be in the form of a "gun on the table" that shoots someone who acted badly and boots them out of the "whitelist".

We especially like Sybil resistant protocols, where everyone can become a player (possibly with staking some value) and the protocol will eventually succeed even in the presence of many Sybil identities of an malicious adversary.

These models might be related to a "high soundness" model where protocols just don't really have to satisfy good soundbess, but rather soundness can be maybe as high as 1-1/poly(n) (in generall let's say it's 1-eps). In this soundness regime, the point is to force the player to deposit x/eps "coins", and then when they do get caught, the amortized penalty over every time they lied comes out to be x.

Papers in such models: (this is a living document -- add more and open a pull request!)

1. Rational Sumchecks by Siyao Guo1, Pavel Hubácek, Alon Rosen, and Margarita Vald: https://eprint.iacr.org/2015/1058.pdf

2. Rational proofs paper: Azar and Micali (STOC 2012)

3. Guo et al. (ITCS 2014)

4. 
