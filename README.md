#CyberTools, CTF tools list



[ Cyptography ]:
	
	-- substitution cipher solver : https://www.guballa.de/substitution-solver
		this website is awsome crack substitution in seconds.
    

    -- john :
        $ john hashfile --mask=?1?1?1?1 --1=abcdef12345
            using custom caracterset to bruteforce with john

    -- encrypted zip file:
        brutefore with fcrackzip
            $ fcrackzip -b -u -v encrypted.zip
        or using john:
            $ zip2john encrypted.zip > hash
 
