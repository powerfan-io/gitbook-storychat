# Create Images & Videos

**Storychat**은 사용자에게 자유로운 이미지와 비디오 생성 환경을 제공합니다. 현재는 이미지 생성 기능만 지원되며, 비디오 생성 기능은 빠른 시일 내에 업데이트될 예정입니다.&#x20;

이미지는 **Create** 탭에서 **Create Image & Video** 버튼을 눌러 **Image Generator**를 호출하거나, Storychat에서 캐릭터와 대화 중에도 생성할 수 있습니다.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

**Create Image & Video** 버튼을 누르면 대화 기능 외에 이미지 생성 환경만을 제공하는 **Image Generator**가 실행됩니다.



<figure><img src="../.gitbook/assets/image (16).png" alt="" width="260"><figcaption></figcaption></figure>

캐릭터와의 대화 중 **Image** 버튼을 눌러 이미지를 생성할 수도 있습니다.





<figure><img src="../.gitbook/assets/image (17).png" alt="" width="188"><figcaption></figcaption></figure>

아래 항목들을 입력하여 간단히 이미지를 생성할 수 있습니다. 모든 이미지 생성에는 Story Point가 소모됩니다.



**Format**

생성할 결과물의 유형을 이미지, 비디오 중 선택합니다.



**Select Image Size**

이미지의 해상도를 설정합니다.



**Select Generation Type**

생성 타입을 설정합니다. 두 가지 타입을 제공합니다.

* Text to Image : 프롬프트를 기반으로 이미지를 생성합니다.
* Image to Image : 업로드한 이미지를 기반으로 프롬프트의 수정 내용을 반영하여 이미지를 생성합니다.



**Seed**

시드로 사용할 값을 입력합니다. 특정 주인공이나 이미지를 지속적으로 등장시키고 싶을 경우, 해당 이미지의 시드 값을 입력하면 새로 생성될 이미지에도 반영됩니다. 기본값은 -1로 랜덤한 결과를 반환합니다.



**Upload Photo**

**Image to Image** 기능을 사용할 경우, 원본으로 사용될 이미지를 업로드합니다



**Positive Prompt**

생성하고 싶은 이미지의 모습을 텍스트로 입력합니다. Positive Prompt에 입력된 프롬프트는 생성될 이미지에 반영됩니다.



**Negative Prompt**

생성될 이미지에서 제거하고 싶은 요소를 입력합니다. Negative Prompt에 입력된 프롬프트는 생성될 이미지에서 제거됩니다.

> ex) 안경을 쓰지 않은 여자를 생성
>
> Positive Prompt : a girl
>
> Negative Prompt : glasses

