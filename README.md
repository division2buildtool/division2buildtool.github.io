��ȫ������2��װ���ߡ���Ϊ��Ϸ[��ȫ������2��](https://www.ubisoft.com/en-us/game/the-division/the-division-2)
�����ĵ������������������.NET MAUI��ܣ���Android��Windows��iOS��macOS�Ϲ���������Ӧ�á�

[![.NET MAUI](https://img.shields.io/badge/.NET-MAUI-000000?labelColor=512bd4)](https://dotnet.microsoft.com/zh-cn/apps/maui)
![Windows](https://img.shields.io/badge/-Windows10-0078D6?labelColor=0078D6&logo=Windows)
![Android](https://img.shields.io/badge/-Android-000000?labelColor=000000&logo=Android)
![iOS&macOS](https://img.shields.io/badge/-iOS_&_macOS-000000?labelColor=000000&logo=Apple)  

## ��Ҫ����

1.  ģ����װ�����ݼ��� 

������װ���棺
![�������](https://img2.imgtp.com/2024/03/27/8NUNSt6O.png) 
��׿��װ���棺
![��׿����](https://img2.imgtp.com/2024/03/27/B6Y6ovZ6.png)

2.  ��Ϸ����չʾ���������ݡ�Ʒ�Ƽӳɡ��츳�б���Ʒ�����ȹ��ܣ�  

![��׿����](https://img2.imgtp.com/2024/03/27/DlifWOlb.png)
![��׿����](https://img2.imgtp.com/2024/03/27/VxMyOt9B.png)

## ����
- [������](https://wwbb.lanzout.com/b03vesg4h)     ����:3z9a

## ϵͳҪ��

ϵͳ           | ��Ͱ汾Ҫ��                     | �Ƽ��汾Ҫ��             
--------------|--------------------------------|---------------------
Windows(x64)  | Windows 10 �汾 1809            |Windows 11
Android       | Android 5.0 (API 21)           |Android 7.0 (API 24) 
iOS           | iOS 11                         |iOS 14 ����߰汾    
macOS         | macOS 10.15                    |macOS 11 ����߰汾

## ��װ
### Windows
- ���֮ǰ��װ�������ֱ��˫����װ���ļ�.msix �԰�װӦ�á�

- ���ڵ�һ�ΰ�װ�����·�ʽ��ѡһ��

- �Զ���װ
  1. �򿪡����á�
  1. Win11 ��򿪡�ϵͳ��ҳ�棬Win10 ��򿪡����ºͰ�ȫ��ҳ��
  1. ѡ�񡾿�����ѡ�ѡ��򿪡�������Աģʽ�����ȴ�ϵͳ��װһЩ��Ҫ���
  1. �� Win10������Ҫ�ٵ�����ѡ��������Դ(������ɢ�ļ�)��װӦ�á�ѡ��
  1. �����ҵ���PowerShell����������ѡ������ִ�в��ԣ���������PowerShell�ű���δǩ������������С�Զ�̽ű���Ҫǩ����
  1. �Ҽ� Install.ps1�ļ���ѡ��ʹ�á�PowerShell���С������Զ���װ����������װ�����
  1. �ڳ�������ʱ����װ�ű����ڰ�װ֤��ʱ��ʾ������Ȩ�ޣ��밴�س�(Enter)������;�ڰ�װ֤��ʱ�������� Y �Լ���
  1. �ȴ���װ��ɣ��Ϳ����ڿ�ʼ�˵����ҵ���ȫ������2��װ���ߡ�������Ҳ�����ʹ��ϵͳ���������ܽ��в��ҡ�
     <details>
       <summary>PowerShell ��������</summary>
         <pre><code>
         �ҵ�������:  Division2BuildTool_**.*.*.0_x64.msix  
         �ҵ�֤��:  Division2BuildTool_**.*.*.0_x64.cer  
         �ڰ�װ��Ӧ�ó���֮ǰ����Ҫִ�����²���:  
         -��װǩ��֤��  
         ��Ҫ���й���Աƾ�ݲ��ܼ�����  ����� UAC ��ʾ��������ʱ�ṩ����Ա���롣    
         �� Enter ������...:  
         ���ڰ�װ֤��...  
         ��Ҫ������֤�鰲װ�����������������Ա֤��洢���С������������صİ�ȫ���գ�ֻ�������δ�����֤��Ľ�����ʱ��Ӧִ     �д˲�����  
         ����ʹ�����Ӧ�ó���ʱ��Ӧ�ֶ��Ƴ�����������֤�顣������ַ�ṩ����ز���˵��:  
         http://go.microsoft.com/fwlink/?LinkId=243053  
         �Ƿ�ȷʵҪ����?  
         [Y] ��(Y)  [N] ��(N)  [?] ���� (Ĭ��ֵΪ��N��):  
         ���ڰ�װӦ�ó���...  
         �ҵ��������:  
         Microsoft.WindowsAppRuntime.1.*.msix  
         �ɹ�: �ɹ���װ��Ӧ�ó���  
         �� Enter ������...:
         </code></pre>
     </details>

- �ֶ���װ
  1. ˫��\Dependencies\x64�ļ����µġ�Microsoft.WindowsAppRuntime.1.*.msix�������װ�����а�װ
  1. ˫����Division2BuildTool_1.*.*.0_x64.cer����֤���ļ�
  1. ѡ�� ����װ֤��...��
  1. ѡ�� �����ؼ���� ����Ȼ��ѡ�� ��һ������
  1. ������û��ʻ����ơ���ʾ���Ƿ������Ӧ�ö��豸���и��ģ�������ѡ�� �ǡ���
  1. �� ��֤�鵼���򵼡� �����У�ѡ�񡰽�����֤��������´洢������
  1. ѡ�����...����Ȼ��ѡ���������ˡ��� ����ѡ��ȷ��������һ��������ɡ���
  1. ˫����Division2BuildTool_1.*.*.0_x64.msix����װ���԰�װӦ�á������ʾ�޷���֤��Ӧ�ð��ķ�����֤�飬˵��ǰ��֤�鰲װ���ɹ��� 

## ��������
- Q����װʱ��ʾ���޷���֤��Ӧ�ð��ķ�����֤�顣����ϵͳ����Ա��Ӧ�ÿ�����Ա��ϵ���Ի�ȡ������֤֤�����Ӧ�ð���������֤Ӧ�ð���ǩ���ĸ�֤�������ֱ��֤��

  - A��δ��װ.cer֤���ļ�������2����һ�ΰ�װ��������
  - A��֤���ļ����ڣ�������δ�����°汾�������ֶ���ϵͳʱ����ĵ�֤����Чʱ�䷶Χ���ٰ�װ�������ǰ֤����Ч��Ϊ2023��11��1�յ�2024��11��1�գ�����װ��ɺ󼴿ɽ�ʱ��Ļأ���Ӱ�����ʹ�á�

- Q��˫��.msix�ļ����ܴ򿪣���ʾѡ��Ӧ���Դ��ļ�
  - A��ȱ��ϵͳ�����Ӧ�ð�װ���򡿣����Դ�Ӧ���̵갲װ�������Ҳ���Բ����Զ���װ�������а�װ���Ƽ���

- Q����װ������ʾ���޷���װӦ�ð����������򿪷���Ա��ҪӦ�ð�
  - A��δ��װ�����װ������˵�����̽��а�װ������Զ���װ�������а�װ

- Q�����ͼ������û�д�
  - A����װ���״�����������Ҫ�Թ���Ա������У���ʼ�˵����Ҽ�Ӧ��ͼ��->���ࣩ


## ��֪����

1.  ��׿CollectionView��ScrollView�п��� [MAUI#17326](https://github.com/dotnet/maui/issues/17326)��[#18505](https://github.com/dotnet/maui/issues/18505)
    - ��ʱ��������׿ƽ̨ʹ��.NET7
1.  ��׿ʹ��CommunityToolkit.Maui��PopupʱLabel������ʾ�����д��� [MCT#1532](https://github.com/CommunityToolkit/Maui/issues/1532)��[#1592](https://github.com/CommunityToolkit/Maui/issues/1592)��[#1664](https://github.com/CommunityToolkit/Maui/issues/1664)��[#1717](https://github.com/CommunityToolkit/Maui/issues/1717)��[#1724](https://github.com/CommunityToolkit/Maui/issues/1724)
    - ��ʱ��������׿ƽ̨ʹ��CommunityToolkit.Maui5.2.0��ʹ��Mopups���



## ��������
### [Visual Studio 2022](https://visualstudio.microsoft.com/zh-hans/vs/)
- ��������
    - ����Ӧ�ú��ƶ�Ӧ��
        - [.NET Multi-platform App UI ����](https://learn.microsoft.com/zh-cn/dotnet/maui/what-is-maui?view=net-maui-8.0)


<div style="display:none">
## ����CLIָ��
- ��¡�����غ�ԭNuget��  
    ```dotnet restore```
- [����Android](https://learn.microsoft.com/zh-cn/dotnet/maui/android/deployment/publish-cli?view=net-maui-7.0)��֤��λ����\<AndroidSigningKeyStore>����һ�£�  
    ```dotnet publish -c:Release -f:net7.0-android /p:AndroidSigningKeyPass=*** /p:AndroidSigningStorePass=***```
- [����Windows](https://learn.microsoft.com/zh-cn/dotnet/maui/windows/deployment/publish-cli?view=net-maui-8.0)���ȵ���.pfx֤�鵽�������  
    ```dotnet publish -c Release -f net8.0-windows10.0.19041.0 /p:RuntimeIdentifierOverride=win10-x64```
- [����iOS](https://learn.microsoft.com/zh-cn/dotnet/maui/ios/deployment/publish-cli?view=net-maui-8.0)��macOS������  
    ```dotnet publish -c Release -f net8.0-ios```
- [����Mac](https://learn.microsoft.com/zh-cn/dotnet/maui/mac-catalyst/deployment/publish-unsigned?view=net-maui-8.0)��macOS������  
    ```dotnet publish -c Release -f net8.0-maccatalyst```
</div>

## ���ݲο���ͼƬ�ز���Դ
- [Division 2 Build Making Tool (TU16)](https://docs.google.com/spreadsheets/d/1gdiqJGR0U9yiSX90mVA4bruWfUyWpmsmWsYz4wY7t3Q)
- [Division 2 Gear Spreadsheet](https://docs.google.com/spreadsheets/d/1nrPBmOrtpkEW1j5fbcRT7L-AXgsGOqMqxXoVtopsiGM)
- [Division 2 Gear Attribute Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vTJEX5DerCvOj3a_m36TRy1gPBAUvrduOIdmXI9j1Y0MpQk1wIXaZ9KOcPa7HzXzp_N5qGmjDj6yEfL/pubhtml)

## ��л���¿�Դ��Ŀ
* [.NET MAUI - MIT License](https://github.com/dotnet/maui)
* [CommunityToolkit.Maui - MIT License](https://github.com/CommunityToolkit/Maui)
* [CommunityToolkit.Mvvm - MIT License](https://github.com/CommunityToolkit/dotnet)
* [LocalizationResourceManager.Maui - MIT License](https://github.com/SirJohnK/LocalizationResourceManager.Maui)
* [Mopups - BSD-3-Clause License](https://github.com/LuckyDucko/Mopups)
* [Newtonsoft.Json - MIT License](https://github.com/JamesNK/Newtonsoft.Json)
