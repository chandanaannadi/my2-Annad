# my2-Annad
 
# CHANDANA ANNADI
###### Vacation Spot: Hyderabad
Hyderabad is my favourite vacation spot in india where I completed my bachelors and got so many friends and enjoyed a lot with them. We used to go to **malls** on weekends, watch movies and do lot of fun with them. Maily we used to play badminton. One day we went to **music concert** of Anirudh in kukatpally. 

----------------------------------------------------------------------

1. Favourite Vacation spot - Hyderabad
   1. Charminar
   2. Wonderla Amusement park
   3. Music concert

- Favourite Food dishes at my Vacation Spot
   - Paradise Biryani
   - KFC
   - Deserts in Naturals
   - Samosa

   **[click here to go to MyStats.md](MyStats.md)**

   *******************************************
   # Table for *introducing famous sports in India*:

    | Sport | Reason | Time Spent |
    | --- | --- | ---: |
    | Cricket | We inherited that love from our glorious conquerors, the British Empire. | 5 hours |
    | Badminton | The dominance of Asia's badminton players at the top level. | 4 hours |
    | Foot Ball | Football is the most popular sport globally. | 6 hours |
    | Chess | Chess has risen in popularity in India in the last few decades. | 2 hours |

    *********************************

    ## Quotes of Scentits

    > “Imagination is more important than knowledge." - *Albert Einstein's*

    > "One never notices what has been done; one can only see what remains to be done." - *Marie Curie's*

    ****
    
# How to put a condition at Datatables button?
success: function(response){
    var result;
    
    if (response.data != null){
        result = "dataNotNull";
    } else {
        result = "dataNull";
    }

    loadFunc(result);
}

function loadFunc(result){
    $('#myTable').DataTable({
        buttons: [
            {
                text: 'Missmatch',
                titleAttr: 'Download in Excel',
                action: function ( e, dt, node, config ) {
                    func_expMissMatch();
                }
            }
            {
                text: 'Not Found',
                titleAttr: 'Download in Excel',
                action: function ( e, dt, node, config ) {
                    func_expNotFound();
                }
            }
        ]
    });
}


**[Here it is a link for checkout](https://stackoverflow.com/questions/77022101/how-to-put-a-condition-at-datatables-button)**


