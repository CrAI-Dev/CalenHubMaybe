local Hub = {
     [6859865958] = {
        [1] = "https://raw.githubusercontent.com/CrAI-Dev/Sac/main/TestHub",
   },
     [6299805723] = {
        [1] = "https://raw.githubusercontent.com/naypramx/youtubesim/main/xxxxx",
   },
     [6612749452] = {
        [1] = "https://raw.githubusercontent.com/naypramx/youtubesim/main/xvav",
   },
}

for i,v in pairs(Hub) do
    if i == game.PlaceId then
        print("CheckScript")
           loadstring(game:HttpGet(v[1]))()
        else
        
        end
    end
    
