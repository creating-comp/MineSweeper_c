#include <stdio.h>
void easy(){
  int count=0, guess=0;
  int arr[9][9]= {
  {0, 1, -1, 1, 0, 0, 0, 1, -1},
  {0, 1, 2, 2, 1, 0, 0,  1,  1},
  {0, 0, 1, -1, 1, 0, 0, 0,  0},
  {0, 0, 1, 1, 1, 0, 0,  1,  1},
  {1, 1, 0, 0, 0, 0, 0,  1, -1},
  {-1, 2, 1, 1, 0, 0, 0, 1,  1},
  {2, 4, -1, 3, 2, 1 , 1, 0, 0}, 
  {-1, 3, -1, -1, 2, -1, 1,0,0},
  {1, 2 , 2, 2, 2, 1, 1, 0,  0}
  };

  int x,y,i,j;
  for (i = 0; i < 9; i++) {
    for (j = 0; j < 9; j++) {
      printf("[]");
    }
    printf("\n");  
  }
  printf("enter a move: ");
  scanf("%d %d",&x, &y);
  count+=1;
  while (x>=9 || y>=9){
    printf("error, enter a move again:");
    scanf("%d %d",&x, &y);
    count+=1;
  }
}
void mid(){
  int arr[16][16];
  int x,y;
  scanf("%d %d",&x, &y);
}
void hard(){
  int arr[16][30];
  int x,y;
  scanf("%d %d",&x, &y);
}
int main() {
  int level;
  
  printf("choose the level:\n");
  printf("1.easy\n");
  printf("2.medium\n");
  printf("3.hard\n");
  
  scanf("%d",&level);
  
  if (level==1)     {  easy();  }
  else if (level==2){   mid();  } 
  else if (level==3){  hard();  }
  
  return 0;
}
