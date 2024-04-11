---
icon: chevron-right
order: 5000
---

``Last update: Mar 10, 2024``

***
:::content-center
<img src="..\appliocolab-img\banner.png" alt="image" width="600">

:::
###### ‎
:::content-center
## 소개 ‎
:::
- Applio 는 <u>[IA Hispano</u>](https://github.com/IAHispano)</u> 팀에서 개발한 <u>[Mangio](https://docs.aihub.wtf/rvc/local/mangio/)</u> 의 <u>[fork](https://docs.aihub.wtf/essentials/whats-rvc/#forks)</u> 입니다.

- 훌륭한 **UI** 및 **많은** 추가 기능. 예를 들어 TTS(RVC 모델로도 이용 가능), 플러그인, 자동 모델 업로드, 커스텀 가능한 테마 등 다양한 기능으로 사랑받고 있습니다.

- 사용자 친화적인 경험과 활발한 개발로 인해 최고의 fork 중 하나로 꼽힙니다.

- 이 클라우드 버전은 <u>[Google Colab](https://docs.aihub.wtf/extra/glossary/#google-colab)</u> 에서 호스팅되므로 런타임이 4시간이라는 점을 기억하세요.
‎         
#### 장점 & 단점 :icon-tasklist:
==- *더 알기*
!!! *장단점은 사람에 따라 다를 수 있습니다.*        
!!! 
||| ✔️ **장점** 
- 매우 완벽함
- 개발이 활발히 진행 중
- TTS 기능
- 자동 모델 업로드
- Mangio-Crepe 있음
- 유저 친화적 UI
||| ❌ **단점** 
- 다른 fork들에 비해 살짝 느림
- 더 불안정함
- 무료 유저 사용 제한
||| 
===
***
###### ‎
:::content-center
## 설정 :icon-download:
:::
###### ‎
1. <u>[여기](https://colab.research.google.com/github/iahispano/applio/blob/master/assets/Applio.ipynb)</u> 에서 colab 스페이스로 들어갑니다..
그런 다음 Google 계정에 로그인합니다.
***
###### ‎
2. **Install Applio** 셀을 실행합니다. 약 2분 정도 소요됩니다.

    <img src="..\appliocolab-img\2-install.png" alt="image" width="260">‎     
‎   
- 왼쪽에 체크 표시가 나타나면 완료입니다.

    <img src="..\appliocolab-img\2-instdone.png" alt="image" width="260">‎     

***
###### ‎
3. 모델을 학습시키려면 데이터셋을 Google 드라이브 저장소에 업로드하고 **Extra** 셀을 실행하세요.

    <img src="..\appliocolab-img\2-extra.png" alt="image" width="260">‎     
‎       
- 시간을 절약하기 위해, 펼치고 & 사용하지 않을 경우 커스텀 사전학습모델 다운로드를 취소하세요.              

    <img src="..\appliocolab-img\2-pretrain.png" alt="image" width="300">‎

***
###### ‎
4. Google 드라이브에 권한을 부여합니다.          
‎   
    <img src="../rvcdisconnected-img/4.png" alt="image" width="400" height="auto">‎   

***
###### ‎
5. **Start Applio**를 실행합니다.

    <img src="..\appliocolab-img\2-start.png" alt="image" width="300">‎     
‎     
- 그리고 **public URL**을 엽니다.

    <img src="..\appliocolab-img\2-url.png" alt="image" width="430">‎   
‎       
!!!warning 사용이 끝날 때까지 Colab을 닫지 마십시오. 작동이 중지됩니다.
!!! 
***
###### ‎       
:::content-center
## 추론론 :icon-unmute:   
!!!success
문제가 발생하면 <u>[문제 해결](https://docs.aihub.wtf/rvc/cloud/applio-colab/#troubleshooting)</u> 을 읽어보세요.
!!!
:::
###### ‎   
#### 1. 음성 모델 업로드
- **Download** 탭으로 이동합니다.       
업로드는 <u>[**모델 링크**](https://docs.aihub.wtf/essentials/voice-models/#how-to-search-voice-models)</u> 를 사용하거나 **직접** 파일을 집어넣습니다.

    +++ 링크
    a. **Download** 탭으로 이동 & `Model Link` 입력란에 링크 붙여넣기.     
    허깅 페이스 또는 Google 드라이브 링크여야 합니다.        
    ‎       
    <img src="..\appliocolab-img\3-download-model.png" alt="image" width="780">    
    ‎       
    b. ``Download Model`` 클릭.
    +++ 직접

    a. Below in **Drop files**, press the upload box & input the model's .PTH. 아래 **Drop files**에서 업로드 박스를 누르고 모델의 .PTH를 선택합니다.   
    ‎       
    <img src="..\appliocolab-img\3-modelupload.png" alt="image" width="800">       
    ‎           
    b. 이후 .INDEX를 선택합니다.
    +++ 

‎  
#### 2. 음성 모델 선택
a. **Inference** 탭으로 돌아가서 오른쪽의 ``Refresh``을 클릭합니다.

    <img src="..\appliocolab-img\3-refresh.png" alt="image" width="500">   


    ‎       
b. ``Voice Model`` 과 `Index File` 드롭다운에서 모델을 선택합니다.

    <img src="..\appliocolab-img\3-voice-model.png" alt="image" width="500">   

  ***
###### ‎  
#### 3. 보컬 선택.      
- Applio를 사용하면 오디오를 개별적으로 또는 일괄적으로 변환할 수 있습니다.
    +++ 개별
    a. 업로드 박스를 누르고 오디오를 선택합니다.      
    ‎   
        <img src="..\appliocolab-img/3-upload.png" alt="image" width="600">‎      
    ‎       
    ‎   
    b. 그런 다음 밑의 드롭다운에서 선택합니다.      
    ‎   
        <img src="..\appliocolab-img/3-select-audio.png" alt="image" width="400">   

    +++ 일괄
    a. **Batch** 탭으로 이동합니다.     
    ‎       
    <img src="..\appliocolab-img/3-batch-upload.png" alt="image" width="360">‎      
    ‎       
    b. Colab의 파일 탐색기로 이동합니다. ``drive``로 이동하여 오디오가 들어 있는 폴더를 마우스 오른쪽 버튼으로 클릭하고 `경로 복사`를 클릭합니다.
    
    c. `Input Folder` 입력란에 경로를 붙여넣습니다.

    - `Output Folder`에 결과물이 출력될 경로 폴더를 정할 수 있습니다.          
  
    - 경로에 공백이나 특수문자가 포함되어 있지 않은지 확인해주세요.    
    +++

‎  
#### 4. 설정 변경 (선택)      
-  더 나은 결과를 위해 <u>[추론 설정](https://docs.aihub.wtf/rvc/resources/inference-settings/)</u>을 수정하려면 `Advanced Settings`을 펼칩니다.

    <img src="..\appliocolab-img/3-advanced.png" alt="image" width="550">‎   
***

###### ‎  
#### 5. Convert.
a. 아래의 ``Convert``을 눌러 오디오를 처리합니다.       

b. 처리가 완료되면 아래의 **오디오 내보내기** 박스에서 결과물을 들어 볼 수 있습니다.      
다운로드하려면 오른쪽에 있는 다운로드 모양을 누르세요.

    <img src="..\appliocolab-img/3-output.png" alt="image" width="450">‎   

***
###### ‎     
###### ‎  
:::content-center
## 학습 :icon-dependabot:
###### ‎   
:::
:::content-center
:::
==- 1. 전처리
###### ‎      
##### a. 모델 이름
###### ‎    
- `Train` 탭으로 이동합니다. `Model Name`에 모델 이름을 입력합니다.       
경로에 공백이나 특수문자가 포함하지 말아주세요.  

    <img src="..\appliocolab-img\4-modelname.png" alt="image" width="550">‎     

***
###### ‎     
##### b. 데이터셋 경로
###### ‎    
i. 아직 업로드하지 않았다면 데이터셋을 구글드라이브 저장공간에 업로드하세요.       
‎       
ii. Colab에서 왼쪽의 폴더( :icon-file-directory-fill: )를 클릭하고 새로고침 버튼을 클릭합니다.     
‎       
   <img src="..\appliocolab-img\4-refresh.png" alt="image" width="220">‎    
‎   
    (모바일 사용자의 경우, 왼쪽 상단의 세 줄을 탭하고 `파일 브라우저 표시`를 탭합니다.)       
‎   
iii. `drive` 폴더를 열고, 데이터셋을 찾고, 우클릭 후 & `경로 복사`를 클릭합니다.     
‎   
    <img src="..\appliocolab-img\4-dtpath.png" alt="image" width="320">‎    
‎    
‎   
iv. 그런 다음 `Dataset Path` 표시줄에 붙여넣습니다.       
‎     
    <img src="..\appliocolab-img\4-dataset.png" alt="image" width="550">‎  

***
###### ‎     
##### c. Sampling Rate
###### ‎    
- 데이터셋의 샘플링 속도를 선택합니다. 모르는 경우 <u>[여기](https://docs.aihub.wtf/rvc/cloud/applio-colab/#extra)</u>를 클릭합니다.

    <img src="..\appliocolab-img\4-samplerate.png" alt="image" width="300">‎  

***
###### ‎     
##### d. Preprocess Dataset
###### ‎    
-  **RVC Version**이 `V2`로 설정되어 있는지 확인한 후, `Preprocess Dataset`를 클릭합니다.     

    출력 상자에 `preprocessed successfully`라고 표시되면 완료입니다.

    <img src="..\appliocolab-img\4-preprocessdone.png" alt="image" width="700">

===

==- 2. 추출
###### ‎    
##### a. Pitch extraction algorithm
###### ‎  
- 원하는 <u>[알고리즘](https://docs.aihub.wtf/rvc/resources/inference-settings/#pitch-extraction-algorithm)</u>을 선택합니다. 나머지는 구식이므로 ``Crepe`` 또는 ``RMVPE``를 사용하세요.

    <img src="..\appliocolab-img\4-f0.png" alt="image" width="400">

***
###### ‎  
##### b. Hop Length (선택)
###### ‎  
- ``Crepe``를 선택한 경우, <u>[홉 길이](https://docs.aihub.wtf/rvc/resources/inference-settings/#mangio-crepe)</u>를 조절할 수 있습니다.

    <img src="..\appliocolab-img\4-hoplength.png" alt="image" width="900">

***
###### ‎  
##### c. Extract Features
###### ‎  
- **Extract Features**을 누릅니다.       
출력 상자에 `extracted successfully`라고 표시되면 완료입니다.

    <img src="..\appliocolab-img\4-extractfinish.png" alt="image" width="350">

===

==- 3. 학습
###### ‎  
##### a. Batch Size
###### ‎  
- 초보자라면 `8`을 사용합니다. 그러나 데이터셋이 짧은 경우(약 2분 이하)에는 `4`를 사용합니다.

    <img src="..\appliocolab-img\4-batchsize.png" alt="image" width="350">

***
###### ‎  
##### b. Save Every Epoch
###### ‎  
- <u>[에포크](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/)</u>를 기준으로 한 <u>[체크포인트 저장](https://docs.aihub.wtf/extra/glossary/#checkpoints)</u> 빈도입니다.    
‎   
- 초보자라면 `15`로 그대로 두세요.             

    <img src="..\appliocolab-img\4-freq.png" alt="image" width="420">‎   
‎   
‎   
- 예시: 값을 ``10``으로 설정하면 에포크 10, 20, 30 ... 처럼 저장됩니다.     
***
###### ‎  
##### c. Total Epoch
###### ‎  
- 모델에 대한 <u>[에포크](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/)</u>(학습 주기)의 총량을 입력합니다.     
‎   
- 하지만 우리는 <u>[텐서보드](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/#tensorboard)</u> 를 사용할 것이므로 '1000'과 같이 임의로 큰 값을 사용합니다.

    <img src="..\appliocolab-img\4-epoch.png" alt="image" width="420">‎   

***
###### ‎  
##### d. Generate Index
###### ‎  
- `Generate Index`을 클릭합니다. 그러면 모델의 <u>[.INDEX](https://docs.aihub.wtf/essentials/voice-models/#voice-model-files)</u> 파일이 생성됩니다.
***
###### ‎  
##### e. 학습 시작
###### ‎  
i. **Save Only Latest** 체크

    <img src="..\appliocolab-img\4-savelatest.png" alt="image" width="240">‎    
‎       
‎   
ii.  아래의 `Start Training`을 눌러 학습 과정을 시작하세요.    
‎   
    <img src="..\appliocolab-img\4-startraining.png" alt="image" width="520">‎   
***
###### ‎  
##### f. 학습 모니터링 
###### ‎  
i. <u>[텐서보드](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/#tensorboard)</u> 는 Colab에서 사용 가능합니다. 만일을 대비해 셀의 로그와 함께 이를 모니터링하는 것을 잊지 마세요.

    로그는 오류가 발생할 경우, 오류와 에포크 및 체크포인트에 대한 정보를 표시합니다.
‎  
    <img src="..\appliocolab-img\4-logs.png" alt="image" width="800">‎   
‎  
‎       
ii. If after around 2:30 hours of training you don't detect <u>[OT](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/#overtraining)</u> <u>[download the model](https://docs.aihub.wtf/rvc/cloud/applio-colab/#c-get-the-pth)</u> of the lowest point, in case it's already OT, and the <u>[.INDEX](https://docs.aihub.wtf/rvc/cloud/applio-colab/#b-get-the-index)</u>.
약 2시간 30분이 지난 후에도 <u>[과학습](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/#overtraining)</u>이 확인되지 않은 경우, 이미 과학습일 경우를 대비하여 가장 낮은 위치에서 <u>[모델 다운로드](https://docs.aihub.wtf/rvc/cloud/applio-colab/#c-get-the-pth)</u> , 그리고 <u>[.INDEX](https://docs.aihub.wtf/rvc/cloud/applio-colab/#b-get-the-index)</u> 를 다운로드 합니다.
‎    
iii. 그런 다음 GPU 런타임이 리셋되면 <u>[재교육](https://docs.aihub.wtf/rvc/cloud/applio-colab/#5-resuming)</U> 절차를 시작합니다.     
***
!!!warning 학습 중에 연결이 끊어질 수 있습니다:  
- 오랫동안 <u>[방치](https://rentry.org/colab_workarounds)</u> 할 경우.    
-인터넷 연결이 끊겼을 경우.      
- 가끔 나오는 캡차를 풀지 않았을 경우.   
- <u>[GPU 런타임](https://docs.aihub.wtf/rvc/extra/glossary/#google-colab)</u> 이 다 사용되었을 경우. 
!!!
===

==- 4. 다운로드
###### ‎  
##### a. 학습 중단
###### ‎  
- 과학습이 확실하다면 **Settings** 탭으로 이동하여 `Restart Applio`을 눌러 학습을 중단할 수 있습니다.

    <img src="../appliocolab-img/4-stoptrain.png" alt="image" width="715" height="auto"> ‎  
‎       
- Colab으로 돌아와서 새 public URL을 엽니다.

***
###### ‎  
##### b. INDEX 얻기
###### ‎     
i. 파일 탐색기를 열고 ``logs``로 이동한 다음, 모델 이름의 폴더를 엽니다.     
‎      
ii. ``added_``라는 이름의 **.INDEX**를 다운로드합니다.  
‎       
   <img src="../appliocolab-img/4-indexdl.png" alt="image" width="400" height="auto">‎
 ‎    

***
###### ‎  
##### c. PTH 얻기
###### ‎  
i. 해당 폴더에는 모든 <u>[체크포인트](https://docs.aihub.wtf/extra/glossary/#checkpoints)</u>도 있습니다.       
‎  
ii. 과적합 지점 **이전**에 가장 **가까운** 지점의 것을 선택하고 새 폴더로 이동시킵니다.

    - 체크포인트는 이 형식으로 구성됩니다: **모델이름_에포크.pth**.  
    예시: ``arianagrande_60e.pth``       
‎  
        <img src="../appliocolab-img/4-checkpoint.png" alt="image" width="200" height="auto">‎  
‎  
‎  
    - 로그에서 에포크 숫자를 확인하여 체크포인트의 스텝 숫자를 확인할 수 있습니다.

        <img src="../appliocolab-img/4-step.png" alt="image" width="600" height="auto">‎  
    ‎          
    ‎    
iii. 이제 끝입니다, 모델을 재미있게 사용해 보세요. 테스트하려면 보통은 일반적인 [추론](https://docs.aihub.wtf/rvc/local/applio/#inference-)를 수행합니다.

===

==- 5. 재시작
###### ‎  
- 학습이 완료되었지만 모델에 여전히 학습이 필요한 경우, 처음부터 다시 시작할 필요는 없습니다.   
  
1. 이전에 입력했던 것과 **동일한 설정 및 기준**을 입력하기만 하면 됩니다. preprocess, feature extract 또는 .INDEX 학습을 다시 수행할 필요가 없습니다.    
 ‎     
2. **save frequency** 를 변경하거나, 이전에 충분히 입력하지 않은 경우 **Total Epoch** 양을 늘릴 수 있습니다.    
 ‎  
3. 새 세션에서 다시 시작하는 경우, Colab에서 **Extra** 셀을 펼치고 이전에 지정한 모델 이름을 입력합니다.     
 ‎  
        <img src="../appliocolab-img/4-retrain.png" alt="image" width="400" height="auto">   ‎       
 ‎  
- 이를 위해서는 이전 세션에서 Auto Backup 셀이 실행되었어야 합니다.     
 ‎  
        <img src="../appliocolab-img/4-autobackup.png" alt="image" width="600" height="auto">   
 ‎  
4. 학습을 다시 시작하고 이전과 마찬가지로 <u>[텐서보드</u>](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/#tensorboard)</u> 를 모니터링하는 것을 잊지 마세요.  
===

###### ‎  
###### ‎  
:::content-center
## TTS
*`+ 아무 RVC 모델과 함께`*
:::
###### ‎  
- Applio는 기본적으로 **다양한** 음성을 선택할 수 있는 하나의 TTS 도구를 제공하는 것으로도 유명합니다.

- 원하는 경우 <u>[추론 설정](https://docs.aihub.wtf/rvc/resources/inference-settings/)</u>을 적용하여 **RVC 모델**과 함께 사용할 수도 있습니다.

- 또한 **Eleven Labs** TTS <u>[플러그인](https://docs.aihub.wtf/rvc/cloud/applio-colab/#plugins)</u> 을 다운로드할 수 있습니다.      
***
###### ‎  
#### <u>지침:</u>
1. **TTS** 탭으로 이동합니다. 

   <img src="../appliocolab-img/5-ttstab.png" alt="image" width="400" height="auto"> ‎ 

***   
###### ‎   

2. RVC 모델을 사용하려면 <u>[다운로드](https://docs.aihub.wtf/rvc/cloud/applio-colab/#1-upload-voice-model)</u> 하고, **TTS**로 이동하여 `Refresh`을 클릭하고 **Voice Model** 과 **Index File**에서 선택합니다.

   <img src="../appliocolab-img/5-vm.png" alt="image" width="600" height="auto">‎    
‎             
- <u>[추론 설정](https://docs.aihub.wtf/rvc/resources/inference-settings/)</u> 또는 TTS/RVC 오디오의 출력 폴더를 수정하려면 `Advanced Settings`을 펼칩니다.

***
###### ‎      
3. **TTS Voices**에서 원하는 언어, 억양 및 성별의 음성을 선택합니다.      

    **Text to Synthesize**에 텍스트를 입력합니다. 그런 다음 `Convert`을 클릭합니다.

   <img src="../appliocolab-img/5-voice.png" alt="image" width="500" height="auto">‎     
‎   
- RVC 모델을 사용하는 경우, 모델과 가장 일치하는 음성을 선택하면 훌륭한 결과를 보장할 수 있습니다.  
***
###### ‎  
4. 완료되면 Export Audio 상자에서 결과를 들을 수 있습니다. 다운로드하려면 오른쪽에 있는 다운로드 버튼( :icon-download: )을 클릭합니다.

   <img src="../appliocolab-img/5-ttsoutput.png" alt="image" width="500" height="auto">‎   

***
###### ‎  
###### ‎  
:::content-center
## Extra
:::
###### ‎  
- Applio에는 <u>[Ilaria](https://ko-fi.com/ilariaowo)</u>에서 만든 **audio analyzer**가 포함된 **Extra** 메뉴가 있습니다.

- 모델을 학습시킬 때 데이터셋의 <u>[샘플링 속도](https://docs.aihub.wtf/rvc/resources/datasets/#sample-rate)</u> 를 편리하게 결정할 수 있습니다.

- 또한 고급 사용자에게 이상적인 **model fusion** 도구도 포함되어 있습니다.

***
###### ‎  
#### <u>Audio Analyzer:</u>
1. **Extra** 탭으로 이동하여 업로드 상자를 눌러 오디오를 선택합니다.

   <img src="../appliocolab-img/6-tab.png" alt="image" width="400" height="auto">‎   
***
###### ‎  
2. 업로드가 완료되면 `Get information about the audio`를 클릭합니다.   

***
###### ‎  
3. **샘플링 속도**에서 오디오의 전체 샘플링 속도를 확인할 수 있습니다. 해당 값을 학습에 사용하세요.

   <img src="../appliocolab-img/6-samplerate.png" alt="image" width="470" height="auto">‎    
###### ‎    
!!!warning <u>WARNING:</u>   
주파수가 스펙트로그램의 상단에 닿지 않는다면, 최대 지점을 확인하고 <U>**2**</u>를 곱합니다.
!!!

###### ‎
{.list-icon}
- #### <u>Example:</u>
   <img src="../appliocolab-img/6-double.png" alt="image" width="470" height="auto">‎       
‎
>이 사진에서는 20kHz까지 도달했습니다. **두 배**로 늘리면 40kHz가 됩니다. 따라서 이상적인 목표 샘플 레이트는 ``40k``입니다.

***
###### ‎
###### ‎
:::content-center
## Plugins
:::
- 플러그인은 Applio에 추가할 수 있는 구성 요소로, 새로운 기능을 추가하고 사용 환경을 개선합니다.

- 이는 대중이 만든 것으로, 무료로 쉽게 설치할 수 있습니다.

- <u>[GitHub 페이지](https://github.com/IAHispano/Applio-Plugins/tree/main)</u> 에서 찾을 수 있습니다. 앞으로 더 많은 기능이 추가될 예정입니다.
***
###### ‎
#### <u>설치:</u>
1. 해당 플러그인의 GitHub 페이지에 액세스하고 원하는 플러그인의 이름을 클릭합니다.

   <img src="../appliocolab-img/7-repo.png" alt="image" width="470" height="auto">‎ 

***
###### ‎
2. ZIP 파일을 클릭합니다.

   <img src="../appliocolab-img/7-zip.png" alt="image" width="470" height="auto">‎   
‎       
- 오른쪽의 다운로드 버튼을 클릭합니다. 그러면 플러그인의 ZIP 파일이 다운로드됩니다.

   <img src="../appliocolab-img/7-dl.png" alt="image" width="470" height="auto">‎ 
***
###### ‎
3. Applio를 열고 **Plugin** 탭으로 이동합니다. 업로드 상자를 누르고 ZIP 파일을 업로드합니다.

   <img src="../appliocolab-img/7-plugins.png" alt="image" width="600" height="auto">‎   

***
###### ‎
3. **Settings** 탭으로 이동한 후 하단의 **Restart Applio**을 클릭합니다. Colab으로 돌아가서 새 public URL을 엽니다.

    그러면 **Plugins** 탭에서 해당 플러그인을 확인할 수 있습니다.

   <img src="../appliocolab-img/7-plugindled.png" alt="image" width="420" height="auto">‎ 

***
###### ‎
###### ‎
:::content-center
## 문제해결
:::
###### ‎ 
==- *제 샘플링 속도와 맞는 옵션이 없습니다.*
###### ‎   

- **<u>32k**</u>보다 낮은 경우: ``32k``를 선택합니다.      
‎   
- **<u>44.1k**</u>인 경우: ``40k``을 선택합니다.  
‎   
- **<u>48k</u>**보다 높은 경우: ``48k``를 선택합니다.

===

==- *음성이 끊어집니다.*
###### ‎   
- 이런 현상을 artifacting이라고 합니다. 이 문제를 해결하려면 <u>[여기](https://docs.aihub.wtf/rvc/resources/artifacting/)</u> 을 참조하세요.

===

==- *GPU 백엔드에 연결할 수 없습니다.*
###### ‎   
- Colab의 <u>[GPU 런타임](https://docs.aihub.wtf/rvc/extra/glossary/#google-colab)</u> 이 소진되었습니다.
===

==- *답을 찾을 수 없었습니다.*
###### ‎   
- 문제를 <u>[여기](https://docs.aihub.wtf/rvc/#contributions)</u> 로 보내세요.
===
***
###### ‎
:::content-center
#### `You have reached the end.`

[!badge variant="info" size="xl" corners="pill" icon="paper-airplane" iconAlign="right" text="Report Issues"](https://docs.aihub.wtf/rvc/#contributions)
:::
