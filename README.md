y = 0
l = 30
w = 30
    
start_time = millis()
elasped_time = millis() - start_time
    

def setup():
    size(630, 480)

def draw():
    global y

    if y >= 480:
        y = 0
    elif elasped_time >= 20:
        y += 3

        
    background(255, 255, 255)
    
    

    
        
    
    
    
    noStroke()
    
    
    
    
    
    
    
    def bubbles():
    
        global l
        global w
        
   
        

    for x in range(15, 640, 30):
    ellipse(x, 15, 30, 30)
    
     for x in range(30, 630, 30):
    ellipse(x, 45, 30, 30)

    
    def random_colours():
        
        import random
        random_colour = random.randint(0,5)
        print(random_colour)
        
        if random_colour == 0:
            random_colour = fill(255, 51, 51)
        if random_colour == 1:
            random_colour = fill(255, 128, 0)
        if random_colour == 2:
            random_colour = fill(255, 255, 0)
        if random_colour == 3:
            random_colour = fill(0, 204, 0)
        elif random_colour == 4:
            random_colour = fill(0, 128, 255)
        else:
            random_colour = fill(153, 51, 255)
            
            
        def main():
            
