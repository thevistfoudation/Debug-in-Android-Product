# Debug-in-Android-Product
## Mục Lục
- [I.Các Tool cần chuẩn bị ?](#What)
- [II.Các bước cài đặt và sử dụng ?](#How)
- [III.Tổng kết  ?](#When)
<a name="What"></a>
## I.Các Tool cần chuẩn bị ?
Sau đây mình sẽ giới thiệu với các bạn các cách debug sản phẩm của các bạn trên android và bạn nào không dùng máy điện thoại android thì cũng không cần lo đâu nhé mình sẽ hướng dẫn debug cả trên PC nữa nhé
- Trước mắt các công cụ cần sử dụng là :
 - Android Studio: https://developer.android.com/studio
 - Blue Stack 5 (cái này thì các bạn có thể dùng những công cụ giả lập khác như LD player hoặc Nox đều được nhé còn mình sẽ sử dụng Blue Stack5)    (https://www.bluestacks.com/vi/bluestacks-5.html)
<a name="How"></a>
## II.Các bước cài đặt và sử dụng ?
- sau khi tải về hãy cài đặt Android studio vs Blue Stack nhé!
- Sau đây là các bước sử dụng debug LogCat của Android Studio:
### Phase 1 setup môi trường:
  - mở android studio lên và create 1 project mới
  - ![image](https://user-images.githubusercontent.com/47918431/151969446-7c3bd153-e9ca-4411-aeb5-919d6e376f22.png)
  - sau đó chọn `Basic Activity` 
  - ![image](https://user-images.githubusercontent.com/47918431/151969589-55d54671-997b-4935-8c35-fed809ff74ef.png)
  - rồi bấm `Next` rồi kế tiếp là `Finish`
  - rồi sau đó cùng đợi đến khi button`LogCat` hiện lên nhé
  - ![image](https://user-images.githubusercontent.com/47918431/151969992-c18db2b8-e1fd-4c13-b92e-cb746cf1d099.png)
  - sau khi bấm vào log cat sẽ hiện lên cửa sổ như trên đây sẽ là cửa sổ hiện thị log cho chúng ta debug phần mềm
 ### Phase 2 Debug log:
  - Cài đặt Blue Stack 5 và sử dụng như những máy Android thông thường như đăng nhập và download những phần mềm cần debug về:
  - ![image](https://user-images.githubusercontent.com/47918431/151970532-af0933cf-0260-4a70-8640-782abb9d3730.png)
  - Sau đó bấm vào setting nhé 
  - ![image](https://user-images.githubusercontent.com/47918431/151970728-e43f3add-6296-4dda-abbb-915282c468ad.png)
  - Sau khi bấm vào Setting sẽ bấm tiếp vào Advance và bật lên các tính năng debug như hình dưới nhé 
  - ![image](https://user-images.githubusercontent.com/47918431/151971073-56925a7d-b39d-467d-a9ec-5ed45d47f775.png)
  - Và đứng quên bấm Save nhé =)))
 ### Phase 3 sử dụng Debug :
  - ở đây mình sẽ check log ví dụ về game nhé: 
  - ![image](https://user-images.githubusercontent.com/47918431/151971599-7cad504d-6921-476e-ab74-dd27bfeb3e83.png)
  - rồi các bạn về màn hình Android Studio để ý log nhé 
  - ![image](https://user-images.githubusercontent.com/47918431/151972105-544b4808-7168-4ea8-a3f5-963d0f1c84c8.png)
  - Đây là thành quả log được ra sau khi mở game lên nhé 
<a name="When"></a>
## III.Tổng Kết ?
- LogCat trong Android Studio là công cụ giúp các lập trình viên check các log được dễ hơn và các issue khó tái hiện trên Editor mà chỉ xảy ra trên product 
- Ngoài check log ra còn có thể giúp những  bạn đang chập chững vào nghề có thể nắm được rõ hơn việc mình muốn học ngôn ngữ gì và phải sử dụng công cụ gì ví dụ như khi check log game bên trên mình đã phát hiện ra Game mình đang chơi sử dụng ngôn ngữ lập trình Thông Dịch LUA. 
- Chúc các bạn sử dụng LogCat để check log và bắt issue sản phẩm smooth hơn nhé 



