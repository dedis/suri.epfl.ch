Randomness is vital to cryptographic security.  Pseudorandom number generation algorithms have been the topic of decades of academic study, and a variety of cryptographic pseudorandom number generation algorithms have been formally standardized over the years.  However, in spite of these formal foundations and standards, cryptographic disasters stemming from flawed random number generator implementations happen with distressing frequency.  We will tour several historical and recent incidents of random number generation disasters including repeated failures to properly seed pseudorandom number generators, repurposed backdoors in the case of the Juniper Dual EC DRBG incident, and cryptographic standards that failed to rule out hardcoded keys in the ANSI X9.31 algorithm, trace these flaws to gaps in understanding between researchers, standards bodies, and implementers, and discuss implications for security and policy moving forward.