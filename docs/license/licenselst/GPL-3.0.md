---
layout: default
title: GPL-3.0
parent: 라이선스별 의무사항
grand_parent: 오픈소스 라이선스
---
# {{ page.title }}

## 라이선스 개요

### 라이선스 요약
GPL-3.0 라이선스는 고지 의무와 함께 <span>전체 코드 공개</span>{: .text-red-400 } 및 <span>User Product 배포 시 설치 정보 제공</span>{: .text-red-400 }에 대한 의무가 존재합니다.


{: .div_box}
> #### 소스 형태로 재배포
>
> - **고지 의무**
>   - 소스 코드 내 명시된 저작권과 라이선스 정보를 그대로 유지한 상태로 재배포합니다.
> - **수정 시 의무사항**
>   - 추가 및 수정한 부분에 GPL-3.0 라이선스를 적용합니다.
>   - 수정 사항에 대한 고지를 포함합니다(예: 수정일, 수정 내용을 주석 형태로 포함).
>
> #### 바이너리 형태로 재배포
>
> - **고지 의무**
>   - 오픈소스 고지문을 생성하여 바이너리 재배포 시 동봉합니다.
> - **수정 시 의무사항**
>   - 추가 및 수정한 부분에 GPL-3.0 라이선스를 적용합니다.
>   - 수정 사항에 대한 고지를 포함합니다(예: 오픈소스 고지문에 수정일, 수정 내용을 포함).
> - **소스 코드 제공 의무**
>   - <span>바이너리에 해당하는 **전체 소스 코드**를 제공</span>{: .text-red-400 }합니다.
>   - 바이너리 배포를 사용하는 사용자가 공개된 <span>소스 코드로 동일한 바이너리를 만들 수 있는 빌드 환경</span>{: .text-red-400 }이 제공되어야 합니다.
> - **설치 정보 제공 의무**
>   - 바이너리를 사용자 제품(User Product)과 함께 배포한다면, 설치 정보(Installation Information)를 함께 제공합니다.
>

### 라이선스 설명

[GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html){:target="_blank" .line}은 2007년 [**자유 소프트웨어 재단\(FSF, Free Software Foundation\)**](http://www.fsf.org/){:target="_blank"}에서 만든 대표적인 카피레프트(Copyleft) 라이선스입니다.  
특징으로는 GPL-2.0과 유사한 의무사항을 갖지만, 사용자 제품(User Product) 배포 시, 설치 정보(Installation Information) 제공을 요구한다는 점이 있습니다.


>  **참고하기**
>
>  GPL-3.0 라이선스에 관한 보다 자세한 내용은 [라이선스 전문](https://opensource.org/licenses/GPL-3.0){:target="_blank"}을 참고합니다.

 

### 소스 코드 내 라이선스 문구
GPL-3.0 라이선스 하에 오픈소스는 일반적으로 소스 코드 상단에 아래와 같은 문구가 존재합니다.


```
Copyright (C) <year> <name of author>
  
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
  
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
  
You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>
```

----

## 배포 형태별 의무사항
### Case 1: 소스 형태로 재배포
GPL-3.0 라이선스 하에 오픈소스를 소스 형태로 재배포 시, 아래의 사항들을 준수합니다.  


#### 고지 의무
소스 코드 내 명시된 저작권 및 라이선스 정보를 그대로 유지한 상태로 재배포합니다.

- 저작권 고지 제공
- 보증 부인 제공
- 라이선스 사본 제공
  

#### 수정 시 의무사항
오픈소스의 소스 코드를 일부 추가 및 수정하였을 경우, 아래의 사항들을 준수합니다.

- 추가 및 수정한 부분에 GPL-3.0 라이선스를 적용합니다.
- 수정 사항에 대한 고지를 포함합니다(예: 수정일, 수정 내용을 주석 형태로 포함).


 
### Case 2: 바이너리 형태로 재배포
GPL-3.0 라이선스 하에 오픈소스를 빌드하여 바이너리 형태로만 재배포 시, 아래의 사항들을 준수합니다.


#### 고지 의무
아래 내용을 포함하는 오픈소스 고지문을 생성하여 바이너리 재배포 시 동봉합니다.

- 저작권 고지 제공
- 보증 부인 제공
- 라이선스 사본 제공


#### 수정 시 의무사항
오픈소스의 소스 코드를 일부 추가 및 수정하였을 경우, 아래 사항을 준수합니다.

- 추가 및 수정한 부분에 대해, GPL-3.0 라이선스를 적용합니다.
- 수정 사항에 대한 고지를 포함합니다(예: 오픈소스 고지문에 수정일, 수정 내용을 포함).



#### 소스 코드 제공 의무
바이너리에 해당하는 소스 코드를 제공합니다. 이때, 아래 사항들을 준수합니다.

1. <span>GPL-3.0 라이선스는 파생 저작물에 대해서도 GPL-3.0을 적용하여 소스 코드를 공개할 것을 요구</span>{: .text-red-400 }합니다. 아래 내용을 참고하여, GPL-3.0 라이선스 하에 오픈소스와 파생 저작물의 소스 코드를 공개합니다.

   {: .div_box }
   >  GPL-3.0 라이선스 파생 저작물의 범위
   >{: .text-red-400 .ft-weight-700 }
   >  일반적인 GPL-3.0 라이선스의 파생 저작물의 범위는 아래와 같습니다.
   > 
   >  - 수정 코드
   >  - GPL 프로그램과 동일한 프로세스에서 동작하는 모듈(Module)
   >  - GPL 프로그램과 링크로 연결한 라이브러리(Library)
   >  - GPL 프로그램을 상속한 클래스(Class)
   >
   >  아래의 경우 GPL의 파생 저작물로 간주하지 않습니다.
   > 
   >  - CD와 같은 매체에 함께 존재하지만 GPL프로그램과 전혀 연동하지 않는 독립 프로그램
   >  - GPL 프로그램과는 별도의 프로그램으로써 파이프(Pipe), 소켓(Socket), IPC, 명령행 인자(Command Line Arguments)로 GPL 프로그램과 통신하는 경우


2. 바이너리 사용자가 공개된 소스 코드로 동일한 바이너리를 만들 수 있는 빌드 환경을 제공합니다. 여기에는 아래 사항이 포함됩니다.
- 툴 체인(Tool chain) 정보
- 빌드 스크립트
- 빌드 방법 (README 파일)

3. 소스 코드 대신 **서면 약정서(Written Offer)**를 제공할 수 있습니다. 여기에는 아래의 내용이 포함되어야 합니다.
- 서면 약정서는 제품 판매 후 3년간 유효합니다.
- 누구에게나 제공합니다.
- 비용 청구를 하지 않습니다(소스 전달을 위해 발생하는 비용 제외).
<div class="div_box">
   이후, 외부로부터 서면 약정서를 근거로 소스 코드 제공을 요청받을 경우, 위에서 언급한 바이너리에 해당하는 소스 코드를 제공해야 합니다. 따라서, 제품을 판매한 회사는 판매 후 최소 3년간 소스 코드를 보관해야 합니다.  
   이때, 바이너리를 사용자 제품(User Product)과 함께 배포한다면, 설치 정보(Installation Information)를 제공해야 합니다.
</div>

#### 설치 정보 제공 의무
바이너리를 사용자 제품(User Product)과 함께 배포한다면, 설치 정보(Installation Information)를 제공해야 합니다.

#### <span class="text-red-400">사용 제한</span>
대부분의 사용자 제품(User Product)은 보안상의 이유로 설치 정보 제공이 불가능합니다. 따라서, **사용자 제품(User Product)으로 배포하는 소프트웨어에는 AGPL-3.0 라이선스의 오픈소스를 사용하지 않습니다.**

### 라이선스 호환성

하나의 프로그램에서 요구하는 의무사항이 상충되는 오픈소스 라이선스들은 양립할 수 없습니다.

아래는 GPL-3.0 라이선스와 충돌하는 라이선스 목록입니다. GPL-3.0 라이선스를 사용하는 프로그램 내에, 아래의 라이선스의 오픈소스들을 포함하지 않도록 합니다.

- Apache-1.1
- Apache-2.0
- BSD-4-Clause
- FTL
- IJG
- OpenSSL
- Python-2.0


>  **참고하기**
>
>  보다 자세한 GPL-3.0 라이선스와 충돌하는 라이선스 목록은 [GPL-Incompatible Free Software Licenses](https://www.gnu.org/licenses/license-list.html#GPLIncompatibleLicenses){:target="_blank"} 문서를 참고합니다.
>
> ✔︎ [OSADL](https://www.osadl.org/){:target="_blank" .line} 체크리스트: [https://www.osadl.org/fileadmin/checklists/unreflicenses/GPL-3.0-only.txt](https://www.osadl.org/fileadmin/checklists/unreflicenses/GPL-3.0-only.txt){:target="_blank"}
