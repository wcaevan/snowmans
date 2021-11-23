import pygame
BLACK=(0,0,0)
WHITE=(255,255,255)
RED=(255,0,0)
GREEN=(0,255,0)
BLUE=(0,0,255)
pygame.display.set_mode(size=(0,0), flags=0,depth=0,display=0)
scn_width=640
scn_height=480
screen=pygame.display.set_mode((scn_height, scn_width))
screen.fill(BLACK)
pygame.draw.circle(screen, WHITE, [250,50],28)
pygame.draw.circle(screen, WHITE, [250,115],34)
pygame.draw.circle(screen, WHITE, [250,190],40)
pygame.draw.circle(screen, BLACK, [270,45],5)
pygame.draw.circle(screen, BLACK, [230,45],5)
pygame.display.flip()
