# RANKENEN

do ImageCtx.h je potreba pridelat unsigned char evp_hash[33]. Pokud se bude jeste delat blake2s, ve slozce s kernelem na HP je nachystanej v adresari POKUS kernelovej modul blake2s. Tenhle modul je mozny podle referencniho kodu v adresari sse/ na github blake2 upravit aby pouzival instrukce SSE/SSSE3. Makefile k blake je taky ve slozce POKUS.
