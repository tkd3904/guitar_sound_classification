# guitar_sound_classification
>> 기타톤 생성 프로젝트 이전에 먼저 기타 이펙트 구분이 가능한지에 관해 진행해봄
>> 각 wav파일을 Mel-spectrogram으로 변환한 뒤 CNN에 적용함
>> ![Image](https://github.com/user-attachments/assets/9d11a6da-a76b-412f-9828-1627926a083c)
# datasets
>> https://egfxset.github.io/
# parameters
>> ![Image](https://github.com/user-attachments/assets/afd54750-1150-477d-9e0a-b01a13cd0a5f)
>> ![Image](https://github.com/user-attachments/assets/b60c11dc-d432-4964-b99a-f10d628da795)
# Loss_Function & Accuracy
>>![Image](https://github.com/user-attachments/assets/449e2840-293e-4775-b3c4-e5bcfcabf668)
>> 20에폭 이후로 오버피팅이 있는거 같음
# Test
>> ![Image](https://github.com/user-attachments/assets/2be91ba7-167e-47cd-b11f-6c8437f0f22c)
>> ![Image](https://github.com/user-attachments/assets/03707e40-9723-4329-b9e8-dd582233967a)
>> 일단은 clean과 other만 구분 가능하고 공간계는 거의 clean으로 분류한다 데이터셋이 부족해서 일어난 일인것 같다.
