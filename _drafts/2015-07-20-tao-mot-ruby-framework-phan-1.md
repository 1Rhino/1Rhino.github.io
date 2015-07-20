---
layout: post
title:  "Tạo một ruby framework - phần 1"
date:   2015-07-20 21:00:00
categories: ky-thuat-lap-trinh
---

Chào bạn. Nếu bạn đang đọc bài viết này thì ít nhiều bạn đã từng làm việc với ngôn ngữ Ruby. Và chắc hẳn nếu bạn là một lập trình viên Ruby thì khả năng cao là bạn là một web developer. Và nếu bạn là ruby web developer thì đến 90% là bạn đã từng hoặc đang là Rails Developer. Và cũng không nói quá rằng nhờ Ruby On Rails mà người ta biết đến Ruby một cách rộng rãi và góp một phần quan trọng trong sự phát triển của cộng đồng Ruby. <br/>
Rails thì quá phổ biến và học rất nhanh để có thể tự làm được một website. Rails hỗ trợ bạn rất nhiều trong các vấn đề thường gặp với lập trình web, giúp bạn đỡ tốn thời gian và công sức để nhanh chóng hoàn thành công việc. Nhưng cũng chính điều này đôi khi lại dễ làm cho lập trình viên Rails trở nên lười hơn. Chúng ta cứ dùng những chức năng có sẵn, những Gem tiện ích mà đôi khi không thực sự hiểu đằng sau nó là gì, nó được tạo ra như thế nào. Sau một thời gian lập trình Rails, mình cũng chợt nhật ra rằng, mình cũng trở nên lười mất rồi. Nếu không <a href="/ky-nang/luyen-tap-co-chu-dich-deliberate-practice/" target="_blank_">học tập và luyện tập một cách nghiêm túc</a> thì mình sẽ mãi không tiến bộ lên được. <br/>
Chính vì vậy, mình quyết định tìm hiểu, học và viết ra một cái <a href="https://rubygems.org/gems/rhino-framework" target="_blank_">Gem nho nhỏ</a> cho riêng mình. Cái Gem này mô phỏng 1 ruby rack-based framework. Ý tưởng và kỹ thuật của Gem này được bắt đầu từ quyển sách <a href="https://rebuilding-rails.com/" target="_blank_">**Rebuilding Rails**</a> của tác giả **Noah Gibbs**. Mình dựa theo nó và có bổ sung các feature, phần mở rộng theo ý thích cá nhân. <br/>
#### Nào cùng bắt đầu tạo ra một **Ruby Framework** nhé! <br/>
<img src="/images/ruby-framework/keep-calm-and-keep-coding.png" alt="Keep calm and keep coding" class="article-img-center">