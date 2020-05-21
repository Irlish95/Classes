#include <iostream>

using namespace std;

class Card{
protected:
    enum Suit{
        HEARTS,
        DIAMONDS,
        SPADES,
        CLUBS,
    };
    enum cardValue{
        SIX = 0,
        SEVEN = 1,
        EIGHT = 2,
        NINE = 3,
        TEN = 4,
        JACK = 5,
        QUEEN = 6,
        KING = 7,
        ACE = 8,
    };
    bool cardPosition;
public:
    Card(bool cardPosition){
        cardPosition = 0;

    }

    bool Flip(){
        bool cardPosition;
        bool h;
        h = cardPosition^1;
        return h;
    }
    int getValue(int value){
        if(value == SIX){
            return 6;
        }
        else if(value == SEVEN){
            return 7;
        }
        else if(value == EIGHT){
            return 8;
        }
        else if(value == NINE){
            return 9;
        }
        else if(value == TEN){
            return 10;
        }
        else if(value == JACK){
            return 10;
        }
        else if(value == QUEEN){
            return 10;
        }
        else if(value == KING){
            return 10;
        }
        else if(value == ACE){
            return 1;
        }
        else return false;
    }

};

int main()
{
    Card card(1);

    cout<<card.Flip()<<endl;
    cout<<card.getValue(10)<<endl;
    return 0;

}
