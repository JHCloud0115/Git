# 버전 생성
버전 = 의미 있는 변화 
(변화는 단순히 그냥 쓰는 거 저장하는 느낌  )

 - 버전 생성자 설정 (한번만 설정)
   - ``git config --global user.name "자    	신의 닉네임"``
	- ``git config --global user.email "자신의 이메일"``
 
 - 파일 버전 관리 시작 
	1.   생성한 파일 추가 
		  ``git add f1.txt`` 
		  
   2.  버전 시작한다고 설정하기 
	    ``git commit`` 선언
	    - 파일 생성첨 `i`누르고 숫자 넣기
	    - 나갈땐 `esc`누르고 `:wq`로 나가기  
	    
	3.   버전 확인 
		``git log`` 
		생성자 정보 및 버전 확인 가능
		바뀐 버전들의 히스토리 확인 가능

	 4. 변경 
		  *   ``git status``   
		       파일 수정 확인 및 버전 관리 되고 있는지 확인
		   * 수정된 파일 역시 ``git add f1.txt`` 로 바뀐 버전 재등록 

version 설정할때 나오는 화면 		
-------
```
1 (#<-version 적으면 됨)
# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#   (use "git push" to publish your local commits)
#
# Changes to be committed:
#       modified:   f1.txt
#
# Untracked files:
#       .gitignore
#
~
~
~
~
~
~
~
~
<ments/GitHub/JHCloud0115/.git/COMMIT_EDITMSG [unix] (01:50 25/11/2020)1,0-1 All
</Documents/GitHub/JHCloud0115/.git/COMMIT_EDITMSG" [unix] 14L, 349B
```		 
		 









