 # RECV:
   ## 45: Host Change
       42[45, 1]
       0: Type
       1: New Host Id
   ## 5: Rate limit 
      42[5,"chat_rate_limit"]
      0: Type
      1: Rate limit
         "chat_rate_limit": You've been typing too fast!
   ## 22: Game End
      42[22]
      0: Type
      This packets ends the game.
   ## 27: Start game
      42[27,1]
      0: Type
      1: No idea.
   ## 16: Game Start State
      42[16,[{},[["eJytlEtuhDAMhu%2BSdahihxDCVSo2rUaVuqo6zApx9zp2wrMwqHSDf8X4i%2BPY6dWbal57haoBraxqkMydlzwtVd57BKfVFy0VoAvUqMmAhnZoB90r4EAKt%2BWzeA4HLWYKRw4H%2F%2BISIIrdFCryFoY%2BKxVFkdUEtym3BA9HbEHgCMuKRZHVxC6ZbRIazFOynlsyiTkRHRNzJaA8ynZMaiF4B1xXoWIu%2Fj%2FYy92ZDVbaYgEPqVZxk4lQM2Gb12lAkLNdIMT0Y5NcOAXAsokP%2B8zlui4EF9itCwxpOkICm8PhCGOjLpX0XdjAZTriHsucz59bZgDt3wnut%2FEHUt3340a%2BUjUFbLCGebihVXKHeAEhPW3ddZL0tryr9K35OTpJgw0tzJ%2FZC7hWq88oZ39y8edt5vLbfMJjV55dh0wWeeo1C3YckFk4Otp0EK26R7LvYj%2FS%2Bv3WqaaPf8c7LFPXgaFnkGoBwCWBmGBdlQapY4B%2B6geyTmKg4pxqH7WP7V0DWBiGH8N6j3g%3D","Simple Arena 1","scrimpypoops","","2023-05-31 06:45:43",-1,null,null,null]],false,1695838970864,[[0,1],[2,1]],644]]
      0: Packet type
      1: State info
         0: No idea.
         1: Map info
            0: Map settings
               0: Map encoded data
               1: Map name
               2: Map author
               3: Map Description
               4: Map date of release
               5-8: No idea, Possibily contributors?
         2: no idea
         3: Unix time at which the game has started
         4: No idea
         5: No idea.
   ## 35: Ping
      42[35,[{"i":0,"p":175}],1-10]
      0: Type 
         1: PLayers ping
            "i": player id
            "p": Their latency
         2: A sort of cycle???
            explanation: each time this packet is sent, that number increases,
            when it hits 10, it is reset.
   ## 9: Player Leave
      42[9, 1, 7, 50867583329]
         0: Type
         1: Player Id whose left
         2: New host
         3: The time at which they left?
   ## 8: Player join
      42[8,["Unnamed Player",true,1,"",3,-1,0,{"1":6372018},false],50865362672]
      0: Type
      1: Player info
         0: Player name
         1: Is guest
         2: No idea.
         3: Peer id?
         4: Player Id
         5: No idea.
         6: Player level.
         7: Player appearence
         8: No idea.
      2: Frame / Unix Time at which player joined?
   ## 12: Recieve input
      42[12,[4,2188,236,3]]
      0: Packet type
      1: Inputs info
         0: Player id whose sent the input
         1: The frame which the input has been sent
         2: The sequence of the input
         3: The input
   ## 7: Room Join
      42[7,[1,0,1695512931394,[["iNeonz",false,1,"",0,13202349,10,{"1":7506175},false],["Unnamed Player",true,1,"",1,-1,0,{"1":6372018},false]],false,false,false,384471,""]]
      0: Packet type
      1: Room Info
         0: Your ID
         1: Host ID
         2: Room ID?
         3: Player list
            0: Player name
            1: Is guest
            2: No idea
            3: Peer Id
            4-5: No idea
            6: Player Level
            7: Player appearence
         4-6: No idea
         7: Room's peer id?
  ## 23: Room link
     42[23, 248901, 'eestj']
        0: Packet type
        1: Room Number
        2: Room Bypass
        Example: This packet forms the link: https://heav.io/248901eestj
  ## 6: Map Change???
     [6, false,["eJytlEtuhDAMhu+SdahihxDCVSo2rUaVuqo6zApx9zp2wrMwqHSDf8X4i+PY6dWbal57haoBraxqkMydlzwtVd57BKfVFy0VoAvUqMmAhnZoB90r4EAKt+WzeA4HLWYKRw4H/+ISIIrdFCryFoY+KxVFkdUEtym3BA9HbEHgCMuKRZHVxC6ZbRIazFOynlsyiTkRHRNzJaA8ynZMaiF4B1xXoWIu/j/Yy92ZDVbaYgEPqVZxk4lQM2Gb12lAkLNdIMT0Y5NcOAXAsokP+8zlui4EF9itCwxpOkICm8PhCGOjLpX0XdjAZTriHsucz59bZgDt3wnut/EHUt3340a+UjUFbLCGebihVXKHeAEhPW3ddZL0tryr9K35OTpJgw0tzJ/ZC7hWq88oZ39y8edt5vLbfMJjV55dh0wWeeo1C3YckFk4Otp0EK26R7LvYj/S+v3WqaaPf8c7LFPXgaFnkGoBwCWBmGBdlQapY4B+6geyTmKg4pxqH7WP7V0DWBiGH8N6j3g=","Simple Arena 1","scrimpypoops","","2023-05-31 06:45:43",-1]]
     0: Packet type
     1: Map info
        0: Map data
        1: Map name
        2: Map author
        3: Map description
        4: The date AND time of when this map was created
        5: No idea.
  ## 41: Change appearence 
     42[41,0,{"1":16711913}]
        0: Packet type
        1: Player who changed their appearence
        2: Appearence
  ## 29: Chat message
     42[29,0,"ayyy"]
        0: Packet type
        1: Player id
        2: The message they sent
 # SEND:
   ## 1:44 Give Host 
      42[1,[44,1]]
         0: Packet Type 
         1: Real Packet
            0: Real Packet Type
            1: New Host ID
   ## 1:15 Start game? 
      42[1,[15,[{},[["eJytlEtuhDAMhu%2BSdahihxDCVSo2rUaVuqo6zApx9zp2wrMwqHSDf8X4i%2BPY6dWbal57haoBraxqkMydlzwtVd57BKfVFy0VoAvUqMmAhnZoB90r4EAKt%2BWzeA4HLWYKRw4H%2F%2BISIIrdFCryFoY%2BKxVFkdUEtym3BA9HbEHgCMuKRZHVxC6ZbRIazFOynlsyiTkRHRNzJaA8ynZMaiF4B1xXoWIu%2Fj%2FYy92ZDVbaYgEPqVZxk4lQM2Gb12lAkLNdIMT0Y5NcOAXAsokP%2B8zlui4EF9itCwxpOkICm8PhCGOjLpX0XdjAZTriHsucz59bZgDt3wnut%2FEHUt3340a%2BUjUFbLCGebihVXKHeAEhPW3ddZL0tryr9K35OTpJgw0tzJ%2FZC7hWq88oZ39y8edt5vLbfMJjV55dh0wWeeo1C3YckFk4Otp0EK26R7LvYj%2FS%2Bv3WqaaPf8c7LFPXgaFnkGoBwCWBmGBdlQapY4B%2B6geyTmKg4pxqH7WP7V0DWBiGH8N6j3g%3D","Simple Arena 1","scrimpypoops","","2023-05-31 06:45:43",-1,null,null,null]],false]]]
        0: Packet type
        1: Real packet
           0: Real packet type
           1: Map info
              0: No idea
              1: Map data
                 0: Map encoded data
                 1: Map name
                 2: Map author
                 3: Map description
                 4: Map data AND time
                 5: No idea
                 6-8: No idea
             2: No idea
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
   ## 1: 21 & 71 END GAME
      42[1,[21]] is called first
      then, proceeded with 42[1,[71]], Which is a response to literally nothing.
   ## 1: 42 & 70 Change map?
      42[1,[42,3560]] is called first then
      42[1,[70,3560]] is called after, it is also a response to literally nothing
        0: Packet type
        1: Real packet
           0: Packet type
           1: Map id
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
      0: Packet type
      1: Real packet
         0: Real Packet type
         1: the entirety of the Map's data, encoded 
   ## 1: 30 Start Typing
      42[1,[30]] this gives you the typing icon, which is taken off after another icon is present or after you send a message.
