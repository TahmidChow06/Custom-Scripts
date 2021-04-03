#! /bin/bash
promptmMssage="LINKS" # Message should of one word
menu="rofi -dmenu -p $promptmMssage -theme ~/Downloads/aur/rofi-collection/minimal/minimal.rasi"
linkType=$(echo -e 'Search Engine\nChat Rooms\nForums\nMarkets' | $menu)

if [ "$linkType" == "Search Engine" ] # Search Engine
then
  search=$(echo -e 'Excavator\nTorch\nnot Evil' | $menu)
    if [ "$search" = "Excavator" ]
    then
      echo '2fd6cemt4gmccflhm6imvdfvli3nf7zn6rfrwpsy7uhxrgbypvwf5fad.onion' | xclip -selection clipboard
    elif [ "$search" = 'Torch' ]
    then
      echo 'cnkj6nippubgycuj.onion' | xclip -selection clipboard
    elif [ "$search" = 'not Evil' ]
    then
      echo 'hss3uro2hsxfogfq.onion' | xclip -selection clipboard
    fi
elif [ "$linkType" == "Chat Rooms" ] # Chat Rooms
then
  search=$(echo -e "John Doe\nBlack Hat Chat\nAbleonion\nThe End Chat\nDaniel's Chat" | $menu)
    if [ "$linkType" = "John Doe" ]
    then
      echo 'tetatl6umgbmtv27.onion' | xclip -selection clipboard
    elif [ "$linkType" = "Black Hat Chat" ]
    then
      echo 'blkhatjxlrvc5aevqzz5t6kxldayog6jlx5h7glnu44euzongl4fh5ad.onion' | xclip -selection clipboard
    elif [ "$linkType" = "Ableonion" ]
    then
      echo 'notbumpz34bgbz4yfdigxvd6vzwtxc3zpt5imukgl6bvip2nikdmdaad.onion' | xclip -selection clipboard
    elif [ "$linkType" = "The End Chat" ]
    then
      echo 'theendgtso35ir6ngdtyhgtjhhbbprmkzl74gt5nyeu3ocr34sfa67yd.onion' | xclip -selection clipboard
    elif [ "$linkType" = "Daniel's Chat" ]
    then
      echo 'danschat356lctri3zavzh6fbxg2a7lo6z3etgkctzzpspewu7zdsaqd.onion' | xclip -selection clipboard
    fi
elif [ "$linkType" == "Forums" ] # Chat Rooms
then
  search=$(echo -e 'Truth Board\nAlien Forum\nCavetor' | $menu)
    if [ "$linkType" = "Truth Board" ]
    then
      echo 'k5aintllrufq23khjnmmfli6uxioboe3ylcao7k72mk2bgvwqb5ek4ad.onion' | xclip -selection clipboard
    elif [ "$linkType" = "Alien Forum" ]
    then
      echo 'alienswjstz7elk6v3x7trrbqmtkcocipqregx7kwzzu44rvs7kaftid.onion' | xclip -selection clipboard
    elif [ "$linkType" = "Cavetor" ]
    then
      echo 'http://cavetord6bosm3sl.onion/forum' | xclip -selection clipboard
    fi
fi
