# guitar_sound_classification
>> 기타톤 생성 프로젝트 이전에 먼저 기타 이펙트 구분이 가능한지에 관해 진행해봄
>> 
>> 각 wav파일을 Mel-spectrogram으로 변환한 뒤 CNN에 적용함
>> ![Image](https://github.com/user-attachments/assets/9d11a6da-a76b-412f-9828-1627926a083c)
>> 
>> (수정 2025-02-05) Mel-spectrogram에 쓸데없는 정보를 다 빼기로 함
>> ![Image](https://github.com/user-attachments/assets/2c893ed1-92c1-4990-a1a9-995f1f458ff9)

>> 해당형태로 라벨 제거
## datasets
>> https://egfxset.github.io/
>>
>> 
## parameters
>> ![Image](https://github.com/user-attachments/assets/afd54750-1150-477d-9e0a-b01a13cd0a5f)
>> ![Image](https://github.com/user-attachments/assets/b60c11dc-d432-4964-b99a-f10d628da795)
>> 
>> Singleclass Classification Model Summary
>> 
>> ![image](https://github.com/user-attachments/assets/559e8a7a-9666-4444-be93-fbcd3578420c)
>> 
>> Multiclass Classification Model summary (배치사이즈 에폭 동일)

## Loss_Function & Accuracy
>>![Image](https://github.com/user-attachments/assets/449e2840-293e-4775-b3c4-e5bcfcabf668)
>>단일 Clean tone만 분류하는 모델
>>
>>(수정 2025-02-05) Multiclass Classification 형태로 수정함
>>![image](https://github.com/user-attachments/assets/08c8ea4d-8635-4c7c-a201-1b280a837cd8)
>>

## Test
>> ![Image](https://github.com/user-attachments/assets/2be91ba7-167e-47cd-b11f-6c8437f0f22c)
>> ![Image](https://github.com/user-attachments/assets/03707e40-9723-4329-b9e8-dd582233967a)
>> 
>> 일단은 clean과 other만 구분 가능하고 공간계는 거의 clean으로 분류한다 데이터셋이 부족해서 일어난 일인것 같다.
>>
>> (수정 2025-02-05) Multiclass Classification 형태로 수정함
>> ![image](https://github.com/user-attachments/assets/15619400-23bd-4338-b06a-198b32dde3a4)
>> 
>> ![image](https://github.com/user-attachments/assets/52457316-2a8a-432b-9d28-646e3a5d3bc8)
>> 
>> ![image](https://github.com/user-attachments/assets/af634f22-bb7c-41e0-b55f-6150c937e3a7)
>> 
>> 데이터셋이 부족한게 아니었고 전처리 잘못한 내 잘못이었음 Pickup position과 Effect 모두 구분 가능함


