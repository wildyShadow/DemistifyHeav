 # RECV:
   ## 35: Ping
      42[35,[{"i":0,"p":175}],1-10]
      0: Type 
         1: PLayers ping
            "i": player id
            "p": Their latency
         2: A sort of cycle???
            explanation: each time this packet is sent, that number increases,
            when it hits 10, it is reset.
 # SEND:
   ##1,15: 
   ## Start game? 
      42[1,[15,[{},[["eJytlEtuhDAMhu%2BSdahihxDCVSo2rUaVuqo6zApx9zp2wrMwqHSDf8X4i%2BPY6dWbal57haoBraxqkMydlzwtVd57BKfVFy0VoAvUqMmAhnZoB90r4EAKt%2BWzeA4HLWYKRw4H%2F%2BISIIrdFCryFoY%2BKxVFkdUEtym3BA9HbEHgCMuKRZHVxC6ZbRIazFOynlsyiTkRHRNzJaA8ynZMaiF4B1xXoWIu%2Fj%2FYy92ZDVbaYgEPqVZxk4lQM2Gb12lAkLNdIMT0Y5NcOAXAsokP%2B8zlui4EF9itCwxpOkICm8PhCGOjLpX0XdjAZTriHsucz59bZgDt3wnut%2FEHUt3340a%2BUjUFbLCGebihVXKHeAEhPW3ddZL0tryr9K35OTpJgw0tzJ%2FZC7hWq88oZ39y8edt5vLbfMJjV55dh0wWeeo1C3YckFk4Otp0EK26R7LvYj%2FS%2Bv3WqaaPf8c7LFPXgaFnkGoBwCWBmGBdlQapY4B%2B6geyTmKg4pxqH7WP7V0DWBiGH8N6j3g%3D","Simple Arena 1","scrimpypoops","","2023-05-31 06:45:43",-1,null,null,null]],false]]]
   
   ## 1: 13 Send inputs
      42[1,[13,[5,1193,187]]] 
         0: Huh! chaz is nesting packets... 
         1:
            0: Packet type 
            1: 
               0: Input 
               1: frame 
               2: sequence
   ## 2: Create room (Account)
      42[2,{"i":4,"a":"8*^^86%ff^GjtudfjHg2","name":"iNeonz's Game","password":"","maxPlayers":1,"hidden":true,"playerName":"iNeonz","peerID":"","token":"my real token here","version":48,"cosmetic":{"1":15601788},"mode":"custom"}]
         0: Packet type
         1: Map data
            "i": No idea
            "a": idk
            "name": game's name
            "password": the password
            "maxPlayers": max players
            "hidden": is it hidden
            "playerName": the host's name?
            "peerID": peer id
            "token": Your token
   ## 1: 21 & 71 END ROOM
      42[1,[21]] is called first
      then, proceeded with 42[1,[71]], Which is a response to literally nothing.
   ## 1: 42 & 70 Change map?
      42[1,[42,3560]] is called first, where 1: [1] is the map ID, then
      42[1,[70,3560]] is also a responde to literally nothing
   ## 1: 40 Change appearence
      42[1,[40,{"1":6372018}]]
        0: the packet type
        1: Real packet
           0: real packet type
           1: object
              "1": the appearence color
   ## 1: 62 Change mode
      42[1,[62,{}]] changes to lives mode
      42[1,[62,{"9":0}]] changes to kills mode
   ## 1: 24 Change team
      42[1,[24,0]] changes to spec
      42[1,[24,1]] changes to ffa
   ## 1: 28 Chat message
      42[1,[28,"ey"]] lololol
   ## 1: 58 Enter Editor
      42[1,[58]] it is the editor icon.
   ## 1: 50 Exit editor
      42[1,[50,"eJzNV81u3CAQfhfOtsUMhsF%2BlWgPTbqtVPVQdZPTat%2B9wIABe5NlpfWqOYQJkPnmj2%2FGZ%2FEq5pezQDEDDboTSswovWDFrDpxCqfkTg0RIbiDP26rD5d77KoVO97Hw%2BVw6c4C3L91XrUZkFWDHeimbulv8%2B%2B1uPo742DA0QuODjiTmOXgTADptqR0wshX3cGPb79PR3fZiPn978fxtjmU4ZOI2RyszFHsdvJ5cRltBpaLqGVtA8fN%2FWsfMlGZFFyKpmW8ceU%2BFmFGLWbxXXRiVG2uYo50Fj91VdfQnGpGbgekDJhjSxmQCkATADEWK5iE9tCAUgAZQxg9itypbm3EwZ1xpvgO74CBqCivrB1WqkEG3VT4kEvAyNbndY83kGiFngeJVQRbeKw5gMwWPdyVG%2FLX8hqWntdCNRMDl32j2f5ubzkCQSKWbAwNSwUGM4BKyVAt9ufHvRZjjJJY4JiaaVSR84dmmt8%2BZ4MKZ6bIOoFQXz2h6quVBnaU95YA80BKE4yPLC9%2B%2B6ATA94OGywZKYSofdN5ZU2Vso6Yb7pLG4jtF5a4hVC%2BVb0pB1XTNRb31uKoR0WRu3FD3ggrVm1xuSwHqsRUkduhgzkBddkmdplumCHQefS0kQKZOtTCSi0FCRAr8ktWQh3j9l%2FMamgqa3CwT5qckGJWm2un9cmjTYWJOxcmcwuqPFi0kHJWVkoJZQ2iZA3S3MTuwYD0wnbEwIRB21n566yorlpxyBVVAkSaSENKWyfO3beUEultnNA1xl7cqtKrHFJb2b2rGAIwVn7aVlR8r%2Bk7eadPDxUf7%2FT4UUBNperdZ5tDJ35514pYcFb9J4MzQEezQhCQp9Vie4zbqtrF67vp8ko118%2F2Ol3fnq5bgjbtp9ynE9geHGJCO%2FH%2BEdc3Xn%2FG%2FdPxXcxnMUbPfcczvqKBC9t%2FZrgfi1za5wvXtqdBMH66GaxPHLiUjAakocvlH6H10Io%3D"]]
   ## 1: 30 Start Typing
      42[1,[30]] this gives you the typing icon, which is taken off after another icon is present or after you send a message.
