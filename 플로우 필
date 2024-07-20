def bfs(board,x,y,c_house):
    dx = [-1,0,1,0]
    dy = [0,-1,0,1]
    
    for i in range(4):
        if board[x+dx[i],y+dy[i]] == '1':
            board[x+dx[i],y+dy[i]] = 0
            c_house += 1
            bfs(board,x+dx[i],y+dy[i],c_house)
    
    return c_house




n = int(input()) #크기 입력
board = [list(input().split()) for i in range(n)] #지도 입력
house = [] #집 개수
cnt = 0 #단지 개수
print(board[1][1])

'''
for i in range(n):
    for j in range(n):
        
        x,y = i,j
        if board[i][j] == '1':
            cnt += 1
            house.append(bfs(board,x,y,0))
                
print(house,cnt)

'''
