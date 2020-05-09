### Understand Text Summarization and create your own summarizer in python

Summarization can be defined as a task of producing a concise and fluent summary while preserving key information and overall meaning.

Impact
Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting.

In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.

Complete article with code and results can be found on [Medium](https://towardsdatascience.com/understand-text-summarization-and-create-your-own-summarizer-in-python-b26a9f09fc70)


### Examples
- Input: 

Khi biết rằng ông Sáu là ba thật của mình, và vết sẹo trên mặt ông là do thằng Mĩ gây nên, buổi sáng cuối cùng trong những ngày phép của ba "Con bé như bị bỏ rơi, lúc đứng vào góc nhà, lúc đứng tựa của và cứ nhìn mọi người đang vây quanh ba nó, vẻ mặt của nó có cái gì hơi khác, nó không bướng bỉnh hay nhăn mày cau có nữa, vẻ mặt nó sẩm lại buồn rầu, cái vẻ buồn trên gương mặt ngây thơ của con bé trông rất dễ thương. Với đôi mi dài uốn cong, và như không bao giờ chớp, đôi mắt nó như to hơn, cái nhìn của nó không ngơ ngác, không lạ lùng, nó nhìn với vẻ nghĩ ngợi sâu xa. " Không hiểu con bé "nghĩ ngợi sâu xa" điều gì, chỉ biết rằng khi ông Sáu buồn rầu quay lại nhìn nó - không dám lại gần sợ nó lại bỏ chạy như lần trước - nói: "Ba đi nghe con" thì nó bất ngờ lao đến thét lên: Ba., a... a...ba! Rồi ôm chặt lấy ông nức nở "Con không cho ba đi". Đến đây, người đọc mới vỡ lẽ ra rằng Thu thèm được gọi ba như thế nào. "Tiếng kêu của nó như tiếng xé, xé sự im lặng và xé cả ruột gan mọi người, nghe thật xót xa. Đó là tiếng "ba" mà nó cố đè nén trong bao nhiêu năm nay, tiếng "ba" như vỡ tung ra từ đáy lòng nó, nó vừa kêu vừa chạy xô tới, nhanh như một con sóc, nó chạy thót lên và dang hai tay ôm chặt lấy cổ ba nó.". Bé Thu là đứa trẻ giàu tình cảm. Thái độ của bé Thu với ba bây giờ trái ngược trong những ngày đầu khi ông Sáu về thăm nhà. Song, trái ngược mà vẫn nhất quán. Vì quá yêu ba, quá khao khát được có ba nên khi nhận định không phải ba nó thì nó nhất định không chịu nhận, nhất định không gọi "ba" lấy một tiếng. Cho nên, khi tiếng gọi như xé kia cất lên ta thấy nó thiêng liêng vô cùng. Tiếng gọi ấy càng trở nên thiêng liêng, quý giá bởi đón chờ nó là cả tấm lòng cao đẹp, thương yêu con vô hạn của người cha.

- Output: 

Thái độ của bé Thu với ba bây giờ trái ngược trong những ngày đầu khi ông Sáu về thăm nhà. Đó là tiếng "ba" mà nó cố đè nén trong bao nhiêu năm nay, tiếng "ba" như vỡ tung ra từ đáy lòng nó, nó vừa kêu vừa chạy xô tới, nhanh như một con sóc, nó chạy thót lên và dang hai tay ôm chặt lấy cổ ba nó.". Cho nên, khi tiếng gọi như xé kia cất lên ta thấy nó thiêng liêng vô cùng. Khi biết rằng ông Sáu là ba thật của mình, và vết sẹo trên mặt ông là do thằng Mĩ gây nên, buổi sáng cuối cùng trong những ngày phép của ba "Con bé như bị bỏ rơi, lúc đứng vào góc nhà, lúc đứng tựa của và cứ nhìn mọi người đang vây quanh ba nó, vẻ mặt của nó có cái gì hơi khác, nó không bướng bỉnh hay nhăn mày cau có nữa, vẻ mặt nó sẩm lại buồn rầu, cái vẻ buồn trên gương mặt ngây thơ của con bé trông rất dễ thương


- Input: 

Năm 2018, tỷ lệ sinh của Hàn Quốc thấp kỷ lục, bình quân mỗi phụ nữ sinh 0,98 con, chưa bằng một nửa so với mức 2,1 cần thiết để duy trì dân số ổn định. Trong 6 năm tới, Hàn Quốc được dự đoán trở thành "xã hội siêu già". Đây được coi là một trong những mối đe dọa lớn nhất đối với nền kinh tế lớn thứ 11 thế giới. Kể từ năm 2006, chính phủ Hàn Quốc chi 152,9 nghìn tỷ won (128,5 tỷ USD) để tăng tỷ lệ sinh. Thông qua chương trình trợ cấp nhà nước, các cặp vợ chồng sắp có em bé có thể nhận 500.000 won (420 USD) để trang trải chi phí trước khi sinh và khoản trợ cấp 107.000 won (89,90 USD) mỗi tháng dành cho phụ huynh có con dưới 5 tuổi.Trung bình người Hàn Quốc làm việc 2.113 giờ một năm - nhiều thứ hai trong số các quốc gia khối Tổ chức Hợp tác và Phát triển Kinh tế (OECD). Chính phủ đã nhận ra tác động của điều này đối với thời gian hẹn hò của thanh niên nên số giờ làm việc trong tuần đã bị cắt giảm từ 68 giờ xuống còn 52 giờ.

- Output: 

 Kể từ năm 2006, chính phủ Hàn Quốc chi 152,9 nghìn tỷ won (128,5 tỷ USD) để tăng tỷ lệ sinh. Thông qua chương trình trợ cấp nhà nước, các cặp vợ chồng sắp có em bé có thể nhận 500.000 won (420 USD) để trang trải chi phí trước khi sinh và khoản trợ cấp 107.000 won (89,90 USD) mỗi tháng dành cho phụ huynh có con dưới 5 tuổi.Trung bình người Hàn Quốc làm việc 2.113 giờ một năm - nhiều thứ hai trong số các quốc gia khối Tổ chức Hợp tác và Phát triển Kinh tế (OECD)

- Input: 

 Anh thanh niên hai mươi bảy tuổi, còn rất trẻ, chưa có người yêu đáng ra phải bay nhảy với cuộc sống, phải vui chơi ở phố phường nhộn nhịp. Anh lại chọn rời xa nơi thành thị ồn ào, rời xa gia đình để gắn bó với công việc vất vả mà vô cùng cô đơn này “đo gió, đo mưa, đo nắng, tính mây, đo chấn động mặt đất, phục vụ sản xuất, phục vụ chiến đấu”. Công việc đầy những khó khăn và nguy hiểm, đòi hỏi sự tỉ mỉ rất cao, vậy mà anh lại đam mê với nó. Công việc phải luôn canh đúng giờ, đối mặt với gió, bão, tuyết, hoang thú và sự cô đơn. Áp lực công việc không có ai để chia sẻ, với một người bình thường chắc họ đã buồn rầu mà sống chẳng có ý nghĩa, nhưng anh luôn sống trong tinh thần lạc quan, một trái tim ấm áp, yêu đời. Anh đã vui sướng biết bao khi kể về câu chuyện khi kịp phát hiện ra các đám mây khô mà từ đó quân ta đã hạ được bao nhiêu phản lực Mĩ trên cầu Hàm Rồng.
 
- Output: 

Công việc phải luôn canh đúng giờ, đối mặt với gió, bão, tuyết, hoang thú và sự cô đơn. Anh lại chọn rời xa nơi thành thị ồn ào, rời xa gia đình để gắn bó với công việc vất vả mà vô cùng cô đơn này “đo gió, đo mưa, đo nắng, tính mây, đo chấn động mặt đất, phục vụ sản xuất, phục vụ chiến đấu”. Áp lực công việc không có ai để chia sẻ, với một người bình thường chắc họ đã buồn rầu mà sống chẳng có ý nghĩa, nhưng anh luôn sống trong tinh thần lạc quan, một trái tim ấm áp, yêu đời
