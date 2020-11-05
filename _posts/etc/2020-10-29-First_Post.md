---
date: 2020-10-29
title: "첫 게시물"
categories: 
  - etc
tags: 
  - etc
  - syntax
read_time: true
toc: false

name: Seyiya
---

### First Post! 

wrote by {{page.name}}


2020-10-29 깃허브 블로그 개설 후 첫 게시글입니다 :)

####  Displaying images

![예시 이미지](/assets/images/open-graph-default.png)

#### Displaying code
```
function test(){
	console.log("something");
}
```

#### Displaying highlighted ruby code
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### Displaying highlighted java code
```java
import java.io.BufferedReader;
import java.io.BufferedWriter;
import java.io.InputStreamReader;
import java.io.OutputStreamWriter;

public class Main{
    public static void main(String args[]){
        BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
        BufferedWriter bw = new BufferedWriter(new OutputStreamWriter(System.out));
        
        try {
        	String[] str;
        	
        	// 가로 세로 입력받고 배열 생성
        	str = br.readLine().split(" "); 
        	int w = Integer.parseInt(str[0]);
        	int h = Integer.parseInt(str[1]);
        	int pan[][] = new int[w][h];

        	// 막대의 개수 n
        	int n = Integer.parseInt(br.readLine());
        	
        	// 각 막대의 길이(l),방향(b),좌표(x,y)
        	int i;
        	for(i=0;i<n;i++) {
        		
        	}
        	for(int i=1;i<20;i++) {
        		
        		for(int j=1;j<20;j++) {
        			bw.write(pan[i][j] + " ");
        		}
        		
        		bw.write("\n");
        	}
        	
        	bw.flush();
        	bw.close();
        	br.close();
        	
        } catch(Exception e) {
        }
    }
    
}

```
