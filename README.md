from pygame import *

class Gamesprite(sprite.Sprite):
    def __init__(self, player_image,player_x,player_y,player_speed,wight,height,):
        super().__init__()



        self.image = tranform.scale(image.load(player_image), (wight,height))
        self.speed = player_speed

        
