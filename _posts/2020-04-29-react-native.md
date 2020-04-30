---
title: 'React Native'
---

_Như đã nói mình sẽ viết về một công nghệ gì đấy mà mình thích, thì mình nghĩ đến một open-source framework mà mình đã dùng cho project tốt nghiệp và mình thấy khá là thích là React Native._

# What is React Native?

Trước hết hiểu về Native, người ta nghĩ đến objects thường tự định dạng mà không phụ thuộc vào host environment (như Web browser). Nó có thể là built-ins, literals hoặc là function definitions. Một số ví dụ về native như là Math, RegExp, Array, String, etc.

React Native là một JavaScript framework được phát triển bởi Facebook dùng để viết và render ứng dụng điện thoại trên có thể dùng được trên cả hai platforms iOS và Android. Tương tự như dùng React để viết một web app, React Native được cấu thành từ JS và JSX nhưng thành phẩm là mobile app. Nói một cách nôm na, React Native như một cái máy chế tạo, bạn cho vào một loại JS code, nó sẽ natively render ra hai loại APIs, Objective-C cho iOS và Java cho Android.

# What are the advatages of using React Native?

First thing first, phải nói là nó cực kì tiện khi bạn muốn tạo mobile app dùng được cho cả hai platforms.

As you know, Java is a pain to deal with and not everyone ẹnjoys the idea of using XCode. Imagine how paranoid it is when you write a mobile app for Android with Java (or either Kotlin), then you have to migrate it into Objectice-C (or Swift) so as you can run it on iOS. It can be a huge waste of time for debugging and troubleshooting as hell. So React Native solved the problem. You don't have to have such a deep knowledge in multiple languages to be able to do that, but just JavaScript. (That doesn't mean you don't need to know a thing about either Java or XCode)

Về developing experience, I gotta say it is such an ease to work with React Native. Đầu tiên về debugging, React Native thường log những tin nhắn lỗi thật sự "có nghĩa" và thật sự cho bạn biết vấn đề nằm ở đâu để sửa. Bởi vì đơn giản nó chỉ là JavaScipt. Thứ hai, bạn không cần phải rebuild toàn bộ application hoặc reset simulator khi có thay đổi mà chỉ cần reload application (not like running an Android Studio emulator or a Xcode simulator, it saves you a tons of time). Last but not least, reusable code, yaay! React Native open-source nên có rất nhiều library để khai thác. Tuy nhiên không phải mọi function hay library hay code bạn viết đều dùng được, hay render giống nhau trên trên cả hai platforms. Điểu này buộc bạn phải có kiến thức về Java và Objective-C để có thể xử lý. Nhưng quan trọng hơn là nhưng phần trăm share codebase của hai version có thể nói là tầm 3/4 application.

# What are the risks and drawbacks?

There is no such thing as a bug free application exist on this earth, so does React Native. It does have its disadvatages.

Phải nói là React Native còn khá là trẻ. Nó chỉ mới ra đời cách 5 năm, vào 2015. Documentation của nó vẫn có chỗ cần được cải thiện hơn.

# My experience on writing React Native

Phải nói là mình khá thích framework này. Nó cho mình suy nghĩ làm mobile app chưa bao giờ dễ dàng và đơn giản đến thế. Từ xuất phát điểm không thích làm web, nó như là lifesaver mình khỏi troublesome Android Studio and XCode (LOL). Nó cho mình xử lý front-end một cách nhẹ nhàng, nhanh chóng và tinh tế với một đứa lề mề chậm chạp với front end như mình. Nó có rất nhiều library cho mình lựa chọn.

Một điểm trừ lớn có lẽ ở việc setting up simulator. Với một MacOS user, mình gặp khá nhiều rắc rối khi plugin emulator cho Android trên macOs của React Native bị deprecated. Mình tốn khá nhiều thời gian tìm cách xử lý, nhưng vẫn chưa tìm được (LOL). Nếu muốn test một function hay giao diện gì đấy trên Android mình phải nhờ teammate (những người dùng windows và linux) giúp với sự hỗ trợ của expo.

# Summary

React Native theo như mình nhận định rất phù hợp với một thị trường năng động mang tính du kích như Việt Nam, khi số lượng người sử dụng không quá lớn và đòi hỏi một ứng dụng nhanh, đa năng với một giao diện đơn giản mang tính hiện đại như hiện nay.

## <br/>

---

# A litte postscript :)

1. Đây thật sự là một bài viết annoying về độ switching ngôn ngữ. Mình lên kế hoạch sẽ dùng tiếng Việt lúc bắt đầu viết bài này, nhưng thật sự có những cụm mình không biết thuật ngữ tiếng Việt của nó là gì và chuyển dần sang tiếng Anh lúc nào không hay. Sau một đoạn break chat chit vơi bạn bè bằng tiếng Việt, mình đã có thể tự tin hơn dùng tiếng Việt triển khai ý trôi chảy hơn. But I was too lazy to translate what I had wrote to Vietnamese so I just left them there :).

2. Thật sự lúc nghĩ về React Native mình có rất nhiều suy nghĩ. Nhưng để sắp xếp ý cho một technical article khó hơn mình nghĩ nhiều. Cuối cùng mình dừng lại ở những ý bề mặt nhất, cơ bản nhất. Mình vẫn chưa có kinh nghiệm gì trong lĩnh vực này. Mình cần phải học thêm ở một bài báo công nghệ cần cover những thứ gì, gửi đến gì cho người đọc hay định hướng của nó nên thế nào. Tất cả những thứ này cần phải học và cải thiện hơn.
