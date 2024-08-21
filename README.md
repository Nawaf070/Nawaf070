# رسم الشاشة
screen.fill(white)
pygame.display.flip()targetFPS = 60
clock = pygame.time.Clock()

#render loop
while True:
        #poll events
        pygame.display.flip()
        clock.tick(60)
