# Lộ trình học 'Machine Learning' từ đầu cho các bạn Lập trình viên.

<p align="center">
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers">
    <img alt="Top-down learning path: Machine Learning for Software Engineers" src="https://img.shields.io/badge/Machine%20Learning-Software%20Engineers-blue.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
</p>

Inspired by [Google Interview University](https://github.com/jwasham/google-interview-university).

Translations: [Brazilian Portuguese](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-pt-BR.md) | [中文版本](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-zh-CN.md)

## Giới thiệu

Đây là kế hoạch dài hơi mà mình sẽ thực hiện để chuyển từ một Lập trình viên di động(mình tự học, không có các cấp) sang vị trí của một kỹ sư Machine Learning. 

Mục đích chính của mình là tìm một cách học Machine Learning thật hiệu quả cho các bạn không có kinh nghiệm nghiên cứu khoa học. Cách học này sẽ tập trung vào việc thực hành các ứng dụng của Machine Learning trước, sau đó mới dần đi vào lý thuyết và toàn học sau.

Các bạn cho mình ý kiến và góp ý để hoàn thiện cách học này nhé!

---

## Mục lục

- [Giới thiệu?](#gioi-thieu)
- [Why use it?](#why-use-it)
- [How to use it](#how-to-use-it)
- [Follow me](#follow-me)
- [Don't feel you aren't smart enough](#dont-feel-you-arent-smart-enough)
- [About Video Resources](#about-video-resources)
- [Prerequisite Knowledge](#prerequisite-knowledge)
- [The Daily Plan](#the-daily-plan)
- [Motivation](#motivation)
- [Machine learning overview](#machine-learning-overview)
- [Machine learning mastery](#machine-learning-mastery)
- [Machine learning is fun](#machine-learning-is-fun)
- [Inky Machine Learning](#inky-machine-learning)
- [Machine learning: an in-depth, non-technical guide](#machine-learning-an-in-depth-non-technical-guide)
- [Stories and experiences](#stories-and-experiences)
- [Machine Learning Algorithms](#machine-learning-algorithms)
- [Beginner Books](#beginner-books)
- [Practical Books](#practical-books)
- [Kaggle knowledge competitions](#kaggle-knowledge-competitions)
- [Video Series](#video-series)
- [MOOC](#mooc)
- [Resources](#resources)
- [Becoming an Open Source Contributor](#becoming-an-open-source-contributor)
- [Games](#games)
- [Podcasts](#podcasts)
- [Communities](#communities)
- [Conferences](#conferences)
- [Interview Questions](#interview-questions)
- [My admired companies](#my-admired-companies)

---

## Tại sao lại học theo cách này?

Mình mong muốn trong tương lai, mình sẽ là một kỹ sư về Machine Learning. Hiện tại thì mình đang là một Lập trình viên mobile(Android, iOS, Blackberry) với 6 năm kinh nghiệm và không có bằng cấp Thạc sĩ, Tiến sĩ gì về Khoa học máy tính cả. Nền tảng kiến thức toán học của mình cũng không được tốt, mình chỉ có chút ít kiến thức về Đại số tuyến tính, Xác xuất thống kê hay Toán rời rạc từ hồi đại học.
Do đó, điều mà mình quan tâm về Machine Learning sẽ là:
- [Tôi có thể học và kiếm được việc làm về Machine Learning khi không có bằng Thạc sĩ hay Tiến sĩ không?](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"Được, nhưng bạn sẽ gặp nhiều khó khăn hơn khi tìm hiểu về Machine Learning."* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)
- [Tôi tự học về Machine Learnng nhưng lại chưa được thực hành và áp dụng nhiều. Vậy thì làm sao tìm được một công việc về Machine Learning với vai trò là một lập trình viên?](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"Tôi đang thuê những chuyên gia về Machine Learning cho team của mình. Thực tế có rất nhiều người có bằng thạc sĩ về Machine Learning sẽ thể có được một công việc về ML, bởi vì những người đó không có hiểu sâu về Machine Learning để giải quyết vần đề của tôi."* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)
- [Làm việc với Machine Learning thì đòi hỏi những kỹ năng gì?](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"Đầu tiên, bạn cần có một nền tảng tốt về Toán học. Machine Learning là một chủ đề khó và nâng cao mà hầu hết những tài liệu về nó đều khuyên bạn nên có nển tảng về toán. Thứ hai, Machine Learning là một chủ đề chung và rất rộng, trong đó có rất nhiều vấn đề nhỏ với những năng năng riêng biệt. Bạn có thể xem các khóa học, giáo trình hay tài liệu về Machine Learning của 'MS program'"* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"Xác xuất, tính toán phân tán, và Thống kê."* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

Qua những tìm hiểu đó mình cũng đúc kết được:

 [Có hai kiểu về Machine Learning](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/):
- Machine Learning theo hướng thực hành: Liên quan đến truy vấn cơ sở dữ liệu, làm sách dữ liệu, viết script để chuyển đổi data và gắn kết thuật toán với các thư viện để giải quyết vấn đề.
- Machine Learning thiên về lý thuyết: Liên quan tới toán học, lý thuyết, nghiên cứu khoa học.

Mình nghĩ cách tốt nhất là tập trung vào việc thực hành, theo kiểu: ['thực hành — tìm hiểu — thực hành'](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985). Nghĩa là đầu tiên các bạn sẽ làm quen với một vài bài toán và thực hành các giải pháp của bài toán đó, để làm quen với hướng xử lý và 1 vài thuật ngữ về Machine Learning. Sau đó mới có thể học lý thuyết trong sách. Cứ thể lặp lại thì các bạn có thể nắm được rõ về bản chất của Machine Learning. Như vậy sẽ dễ tiếp cận hơn việc đọc sách khô khan.

 Đây là một kế hoạch dài hạn, với mình thì sẽ mất vài năm để theo đuổi, còn nếu bạn đã có kiến thức nền tảng tốt thì sẽ mất ít hơn.

## Cách áp dụng phương pháp này
Những thứ bên dưới chỉ là phác thảo, chung chung, các bạn nên xắp sếp các mục theo thứ tự từ trên xuống dưới.

Mình sử dụng markdown của Github để tạo danh mục và cập nhật quá trình học của mình.

- [x] Create a new branch so you can check items like this, just put an x in the brackets: [x]

[Xem thêm về Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## Follow me
Mình là một kỹ sư phần mềm người Việt Nam. Mình có mong muốn là được làm việc ở nước Mỹ.

Thời gian mình dành để thực hiện kế này trong ngày là khoảng 4 giờ đồng hồ sau khi đi làm về.

- Twitter: [@Nam Vu](https://twitter.com/zuzoovn)

| ![Nam Vu - Top-down learning path: machine learning for software engineers](http://sv1.upsieutoc.com/2016/10/08/331f241c8da44d0c43e9324d55440db6.md.jpg)|
|:---:|
| USA as heck |

## Đừng lo khi bạn chưa đủ thông minh
Hầu hết những tài liệu, sách, hay các khóa học về Machine Learning đều khuyên là cần phải có nền tảng tốt về toán như: Đại số tuyến tính, xác suất thống kê hay toán rời rạc. Nhưng dốt cuộc mình vẫn không biết làm sao để bắt đầu...

- [Sẽ ra sao nếu tôi không giỏi toán?](http://machinelearningmastery.com/what-if-im-not-good-at-mathematics/)
- [5 Kỹ thuật để hiểu các thuật toán của Machine learning khi không giỏi toán](http://machinelearningmastery.com/techniques-to-understand-machine-learning-algorithms-without-the-background-in-mathematics/)
- [Tôi nên học Machine Learning như thế nào?](https://www.quora.com/Machine-Learning/How-do-I-learn-machine-learning-1)

## Nguồn video tham khảo

Một số video chỉ có khi tham gia vào khóa học trên Coursera hay EdX. Chúng hoàn toàn miễn phí nhưng phải chờ vài tháng các khóa học đó mới mở tiếp. Vì vậy mình dự định sẽ add những link video vào bài viết này để các bạn dễ kiếm.

## Những kiến thức cần có

Dưới đây là những thứ mà mình cần phải học trước khi bắt đâu thực hiện kế hoạch này:

- [ ] [Phân biệt: Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
- [ ] [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn)
- [ ] [Đừng ngắt ngoãng](http://lifehacker.com/281626/jerry-seinfelds-productivity-secret)
- [ ] [Làm sao để học theo cách của bạn](https://metacademy.org/roadmaps/rgrosse/learn_on_your_own)

## Kế hoạch hàng ngày

Mỗi chủ đề đưa ra thì không nhất thiết phải hoàn thành hay phải hiểu hết nó trong một ngày.

Mỗi ngày lấy một chủ đề từ danh mục, học và note lại, rồi thực hành các bài tập, sử dụng Python hoặc R.

# Động lực
- [ ] [Dream](https://www.youtube.com/watch?v=g-jwWYX7Jlo)

## Machine learning overview
- [ ] [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] [A Gentle Guide to Machine Learning](https://blog.monkeylearn.com/a-gentle-guide-to-machine-learning/)
- [ ] [Introduction to Machine Learning for Developers](http://blog.algorithmia.com/introduction-machine-learning-developers/)
- [ ] [Machine Learning basics for a newbie](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/)
- [ ] [How do you explain Machine Learning and Data Mining to non Computer Science people?](https://www.quora.com/How-do-you-explain-Machine-Learning-and-Data-Mining-to-non-Computer-Science-people)
- [ ] [Machine Learning: Under the hood. Blog post explains the principles of machine learning in layman terms. Simple and clear](https://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)
- [ ] [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=1)
- [ ] [Deep Learning - A Non-Technical Introduction](http://www.slideshare.net/AlfredPong1/deep-learning-a-nontechnical-introduction-69385936)

## Machine learning mastery
- [ ] [The Machine Learning Mastery Method](http://machinelearningmastery.com/machine-learning-mastery-method/)
- [ ] [Machine Learning for Programmers](http://machinelearningmastery.com/machine-learning-for-programmers/)
- [ ] [Applied Machine Learning with Machine Learning Mastery](http://machinelearningmastery.com/start-here/)
- [ ] [Python Machine Learning Mini-Course](http://machinelearningmastery.com/python-machine-learning-mini-course/)
- [ ] [Machine Learning Algorithms Mini-Course](http://machinelearningmastery.com/machine-learning-algorithms-mini-course/)

## Machine learning is fun
- [ ] [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)
- [ ] [Part 2: Using Machine Learning to generate Super Mario Maker levels](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b)
- [ ] [Part 3: Deep Learning and Convolutional Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)
- [ ] [Part 4: Modern Face Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)
- [ ] [Part 5: Language Translation with Deep Learning and the Magic of Sequences](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)
- [ ] [Part 6: How to do Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a#.lhr1nnpcy)

## [Inky Machine Learning](https://triskell.github.io/2016/11/15/Inky-Machine-Learning.html)
- [ ] [Part 1: What is Machine Learning ?](https://triskell.github.io/2016/10/23/What-is-Machine-Learning.html)
- [ ] [Part 2: Supervised Learning and Unsupervised Learning](https://triskell.github.io/2016/11/13/Supervised-Learning-and-Unsupervised-Learning.html)

## Machine learning: an in-depth, non-technical guide
- [ ] [Overview, goals, learning types, and algorithms](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide/)
- [ ] [Data selection, preparation, and modeling](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-2/)
- [ ] [Model evaluation, validation, complexity, and improvement](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-3/)
- [ ] [Model performance and error analysis](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-4/)
- [ ] [Unsupervised learning, related fields, and machine learning in practice](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-5/)

## Stories and experiences
- [ ] [Machine Learning in a Week](https://medium.com/learning-new-stuff/machine-learning-in-a-week-a0da25d59850#.tk6ft2kcg)
- [ ] [Machine Learning in a Year](https://medium.com/learning-new-stuff/machine-learning-in-a-year-cdb0b0ebd29c#.hhcb9fxk1)
- [ ] [How I wrote my first Machine Learning program in 3 days](http://blog.adnansiddiqi.me/how-i-wrote-my-first-machine-learning-program-in-3-days/)
- [ ] [Learning Path : Your mentor to become a machine learning expert](https://www.analyticsvidhya.com/learning-path-learn-machine-learning/)
- [ ] [You Too Can Become a Machine Learning Rock Star! No PhD](https://backchannel.com/you-too-can-become-a-machine-learning-rock-star-no-phd-necessary-107a1624d96b#.g9p16ldp7)
- [ ] How to become a Data Scientist in 6 months: A hacker’s approach to career planning
    - [Video](https://www.youtube.com/watch?v=rIofV14c0tc)
    - [Slide](http://www.slideshare.net/TetianaIvanova2/how-to-become-a-data-scientist-in-6-months)
- [ ] [5 Skills You Need to Become a Machine Learning Engineer](http://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html)
- [ ] [Are you a self-taught machine learning engineer? If yes, how did you do it & how long did it take you?](https://www.quora.com/Are-you-a-self-taught-machine-learning-engineer-If-yes-how-did-you-do-it-how-long-did-it-take-you)
- [ ] [How can one become a good machine learning engineer?](https://www.quora.com/How-can-one-become-a-good-machine-learning-engineer)
- [ ] [A Learning Sabbatical focused on Machine Learning](http://karlrosaen.com/ml/)

## Machine Learning Algorithms
- [ ] [10 Machine Learning Algorithms Explained to an ‘Army Soldier’](https://www.analyticsvidhya.com/blog/2015/12/10-machine-learning-algorithms-explained-army-soldier/)
- [ ] [Top 10 data mining algorithms in plain English](https://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)
- [ ] [10 Machine Learning Terms Explained in Simple English](http://blog.aylien.com/10-machine-learning-terms-explained-in-simple/)
- [ ] [A Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)
- [ ] [The 10 Algorithms Machine Learning Engineers Need to Know](https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa#.ofc7t2965)
- [ ] [Comparing supervised learning algorithms](http://www.dataschool.io/comparing-supervised-learning-algorithms/)
- [ ] [Machine Learning Algorithms: A collection of minimal and clean implementations of machine learning algorithms](https://github.com/rushter/MLAlgorithms)

## Beginner Books
- [ ] [Data Smart: Using Data Science to Transform Information into Insight 1st Edition](https://www.amazon.com/Data-Smart-Science-Transform-Information/dp/111866146X)
- [ ] [Data Science for Business: What you need to know about data mining and data­ analytic-thinking](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323/)
- [ ] [Predictive Analytics: The Power to Predict Who Will Click, Buy, Lie, or Die](https://www.amazon.com/Predictive-Analytics-Power-Predict-Click/dp/1118356853)

## Practical Books
- [ ] [Machine Learning for Hackers](https://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714)
    - [GitHub repository(R)](https://github.com/johnmyleswhite/ML_for_Hackers)
    - [GitHub repository(Python)](https://github.com/carljv/Will_it_Python)
- [ ] [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka-ebook/dp/B00YSILNL0)
    - [GitHub repository](https://github.com/rasbt/python-machine-learning-book)
- [ ] [Programming Collective Intelligence: Building Smart Web 2.0 Applications](https://www.amazon.com/Programming-Collective-Intelligence-Building-Applications-ebook/dp/B00F8QDZWG)
- [ ] [Machine Learning: An Algorithmic Perspective, Second Edition](https://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1466583282)
    - [GitHub repository](https://github.com/alexsosn/MarslandMLAlgo)
    - [Resource repository](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)
- [ ] [Introduction to Machine Learning with Python: A Guide for Data Scientists](http://shop.oreilly.com/product/0636920030515.do)
    - [GitHub repository](https://github.com/amueller/introduction_to_ml_with_python)
- [ ] [Data Mining: Practical Machine Learning Tools and Techniques, Third Edition](https://www.amazon.com/Data-Mining-Practical-Techniques-Management/dp/0123748569)
    - Teaching material
        - [Slides for Chapters 1-5 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch1-5.zip)
        - [Slides for Chapters 6-8 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch6-8.zip)
- [ ] [Machine Learning in Action](https://www.amazon.com/Machine-Learning-Action-Peter-Harrington/dp/1617290181/)
    - [GitHub repository](https://github.com/pbharrin/machinelearninginaction)
- [ ] [Reactive Machine Learning Systems(MEAP)](https://www.manning.com/books/reactive-machine-learning-systems)
    - [GitHub repository](https://github.com/jeffreyksmithjr/reactive-machine-learning-systems)
- [ ] [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
    - [GitHub repository(R)](http://www-bcf.usc.edu/~gareth/ISL/code.html)
    - [GitHub repository(Python)](https://github.com/JWarmenhoven/ISLR-python)
    - [Videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
- [ ] [Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python)
    - [GitHub repository](https://github.com/luispedro/BuildingMachineLearningSystemsWithPython)
- [ ] [Learning scikit-learn: Machine Learning in Python](https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python)
    - [GitHub repository](https://github.com/gmonce/scikit-learn-book)
- [ ] [Probabilistic Programming & Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
- [ ] [Probabilistic Graphical Models: Principles and Techniques](https://www.amazon.com/Probabilistic-Graphical-Models-Principles-Computation/dp/0262013193)
- [ ] [Machine Learning: Hands-On for Developers and Technical Professionals](https://www.amazon.com/Machine-Learning-Hands-Developers-Professionals/dp/1118889061)
    - [Machine Learning Hands-On for Developers and Technical Professionals review](https://blogs.msdn.microsoft.com/querysimon/2015/01/01/book-review-machine-learning-hands-on-for-developers-and-technical-professionals/)
    - [GitHub repository](https://github.com/jasebell/mlbook)
- [ ] [Learning from Data](https://www.amazon.com/Learning-Data-Yaser-S-Abu-Mostafa/dp/1600490069)
    - [Online tutorials](https://work.caltech.edu/telecourse.html)
- [ ] [Reinforcement Learning: An Introduction (2nd Edition)](https://webdocs.cs.ualberta.ca/~sutton/book/the-book-2nd.html)
    - [GitHub repository](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
- [ ] [Machine Learning with TensorFlow(MEAP)](https://www.manning.com/books/machine-learning-with-tensorflow)
    - [GitHub repository](https://github.com/BinRoot/TensorFlow-Book)

## Kaggle knowledge competitions
- [ ] [Kaggle Competitions: How and where to begin?](https://www.analyticsvidhya.com/blog/2015/06/start-journey-kaggle/)
- [ ] [How a Beginner Used Small Projects To Get Started in Machine Learning and Compete on Kaggle](http://machinelearningmastery.com/how-a-beginner-used-small-projects-to-get-started-in-machine-learning-and-compete-on-kaggle)
- [ ] [Master Kaggle By Competing Consistently](http://machinelearningmastery.com/master-kaggle-by-competing-consistently/)

## Video Series
- [ ] [Machine Learning for Hackers](https://www.youtube.com/playlist?list=PL2-dafEMk2A4ut2pyv0fSIXqOzXtBGkLj)
- [ ] [Fresh Machine Learning](https://www.youtube.com/playlist?list=PL2-dafEMk2A6Kc7pV6gHH-apBFxwFjKeY)
- [ ] [Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
- [ ] [Everything You Need to know about Machine Learning in 30 Minutes or Less](https://vimeo.com/43547079)
- [ ] [A Friendly Introduction to Machine Learning](https://www.youtube.com/watch?v=IpGxLWOIZy4)
- [ ] [Nuts and Bolts of Applying Deep Learning - Andrew Ng](https://www.youtube.com/watch?v=F1ka6a13S9I)
- [ ] BigML Webinar
    - [Video](https://www.youtube.com/watch?list=PL1bKyu9GtNYHcjGa6ulrvRVcm1lAB8he3&v=W62ehrnOVqo)
    - [Resources](https://bigml.com/releases)
- [ ] [mathematicalmonk's Machine Learning tutorials](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA)
- [ ] [Machine learning in Python with scikit-learn](https://www.youtube.com/playlist?list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A)
    - [GitHub repository](https://github.com/justmarkham/scikit-learn-videos)
    - [Blog](http://blog.kaggle.com/author/kevin-markham/)
- [ ] [My playlist – Top YouTube Videos on Machine Learning, Neural Network & Deep Learning](https://www.analyticsvidhya.com/blog/2015/07/top-youtube-videos-machine-learning-neural-network-deep-learning/)
- [ ] [16 New Must Watch Tutorials, Courses on Machine Learning](https://www.analyticsvidhya.com/blog/2016/10/16-new-must-watch-tutorials-courses-on-machine-learning/)
- [ ] [DeepLearning.TV](https://www.youtube.com/channel/UC9OeZkIwhzfv-_Cb7fCikLQ)
- [ ] [Learning To See](https://www.youtube.com/playlist?list=PLiaHhY2iBX9ihLasvE8BKnS2Xg8AhY6iV)
- [ ] [Neural networks class - Université de Sherbrooke](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
- [ ] [21 Deep Learning Videos, Tutorials & Courses on Youtube from 2016](https://www.analyticsvidhya.com/blog/2016/12/21-deep-learning-videos-tutorials-courses-on-youtube-from-2016/)
- [ ] [30 Top Videos, Tutorials & Courses on Machine Learning & Artificial Intelligence from 2016](https://www.analyticsvidhya.com/blog/2016/12/30-top-videos-tutorials-courses-on-machine-learning-artificial-intelligence-from-2016/)
- [ ] [Practical Deep Learning For Coders](http://course.fast.ai/index.html)

## MOOC
- [ ] [Udacity’s Intro to Machine Learning](https://www.udacity.com/course/intro-to-machine-learning--ud120)
    - [Udacity Intro to Machine Learning Review](http://hamelg.blogspot.com/2014/12/udacity-intro-to-machine-learning-review.html)
- [ ] [Udacity’s Supervised, Unsupervised & Reinforcement](https://www.udacity.com/course/machine-learning--ud262)
- [ ] [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/learn/ml-foundations)
- [ ] [Coursera’s Machine Learning](https://www.coursera.org/learn/machine-learning)
    - [Video only](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
    - [Coursera Machine Learning review](https://rayli.net/blog/data/coursera-machine-learning-review/)
    - [Coursera: Machine Learning Roadmap](https://metacademy.org/roadmaps/cjrd/coursera_ml_supplement)
- [ ] [Machine Learning Distilled](https://code.tutsplus.com/courses/machine-learning-distilled)
- [ ] [BigML training](https://bigml.com/training)
- [ ] [Coursera’s Neural Networks for Machine Learning](https://www.coursera.org/learn/neural-networks)
    - Taught by Geoffrey Hinton, a pioneer in the field of neural networks
- [ ] [Machine Learning - CS - Oxford University](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
- [ ] [Creative Applications of Deep Learning with TensorFlow](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info)
- [ ] [Intro to Descriptive Statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [ ] [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [ ] [6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/)
- [ ] [6.S191: Introduction to Deep Learning](http://introtodeeplearning.com/index.html)

## Resources
- [ ] [Learn Machine Learning in a Single Month](https://elitedatascience.com/machine-learning-masterclass)
- [ ] [The Non-Technical Guide to Machine Learning & Artificial Intelligence](https://medium.com/@samdebrule/a-humans-guide-to-machine-learning-e179f43b67a0#.cpzf3a5c0)
- [ ] [Best practices rule book for Machine Learning engineering from Google](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [ ] [Machine Learning for Software Engineers on Hacker News](https://news.ycombinator.com/item?id=12898718)
- [ ] [Machine Learning for Developers](https://xyclade.github.io/MachineLearning/)
- [ ] [Machine Learning Advice for Developers](https://dev.to/thealexlavin/machine-learning-advice-for-developers)
- [ ] [Machine Learning For Complete Beginners](http://pythonforengineers.com/machine-learning-for-complete-beginners/)
- [ ] [Getting Started with Machine Learning: For absolute beginners and fifth graders](https://medium.com/@suffiyanz/getting-started-with-machine-learning-f15df1c283ea#.yjtiy7ei9)
- [ ] [How to Learn Machine Learning: The Self-Starter Way](https://elitedatascience.com/learn-machine-learning)
- [ ] [Machine Learning Self-study Resources](https://ragle.sanukcode.net/articles/machine-learning-self-study-resources/)
- [ ] [Level-Up Your Machine Learning](https://metacademy.org/roadmaps/cjrd/level-up-your-ml)
- [ ] [An Honest Guide to Machine Learning](https://medium.com/axiomzenteam/an-honest-guide-to-machine-learning-2f6d7a6df60e#.ib12a1yw5)
- [ ] Enough Machine Learning to Make Hacker News Readable Again
    - [Video](https://www.youtube.com/watch?v=O7IezJT9uSI)
    - [Slide](https://speakerdeck.com/pycon2014/enough-machine-learning-to-make-hacker-news-readable-again-by-ned-jackson-lovely)
- [ ] [Dive into Machine Learning](https://github.com/hangtwenty/dive-into-machine-learning)
- [ ] [{Machine, Deep} Learning for software engineers](https://speakerdeck.com/pmigdal/machine-deep-learning-for-software-engineers)
- [ ] [Deep Learning For Beginners](https://deeplearning4j.org/deeplearningforbeginners.html)
- Machine Learning courses in Universities
    - [ ] [Stanford](http://ai.stanford.edu/courses/)
    - [ ] [Machine Learning Summer Schools](http://mlss.cc/)
    - [ ] [Oxford](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
    - [ ] [Cambridge](http://mlg.eng.cam.ac.uk/)
- Flipboard Topics
    - [Machine learning](https://flipboard.com/topic/machinelearning)
    - [Deep learning](https://flipboard.com/topic/deeplearning)
    - [Artificial Intelligence](https://flipboard.com/topic/artificialintelligence)
- Medium Topics
    - [Machine learning](https://medium.com/tag/machine-learning/latest)
    - [Deep learning](https://medium.com/tag/deep-learning)
    - [Artificial Intelligence](https://medium.com/tag/artificial-intelligence)
- Monthly top 10 articles
    - Machine Learning
        - [July 2016](https://medium.mybridge.co/top-ten-machine-learning-articles-for-the-past-month-9c1202351144#.lyycen64y)
        - [August 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-2f3cb815ffed#.i9ee7qkjz)
        - [September 2016](https://medium.mybridge.co/machine-learning-top-10-in-september-6838169e9ee7#.4jbjcibft)
        - [October 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-35c37825a943#.td5im1p5z)
        - [November 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-b499e4213a34#.7k39i08tv)
        - [Year 2016](https://medium.mybridge.co/machine-learning-top-10-of-the-year-v-2017-7552599935c0#.wtx2mchqn)
    - Algorithms
        - [September 2016](https://medium.mybridge.co/algorithm-top-10-articles-in-september-8a0e6afb0807#.hgjzuyxdb)
        - [October-November 2016](https://medium.mybridge.co/algorithm-top-10-articles-v-november-e73cba2fa87e#.kothimkhb)
- [Comprehensive list of data science resources](http://www.datasciencecentral.com/group/resources/forum/topics/comprehensive-list-of-data-science-resources)
- [DigitalMind's Artificial Intelligence resources](http://blog.digitalmind.io/post/artificial-intelligence-resources)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [CreativeAi's Machine Learning](http://www.creativeai.net/?cat%5B0%5D=machine-learning)

## Games
- [Halite: A.I. Coding Game](https://halite.io/)
- [Vindinium: A.I. Programming Challenge](http://vindinium.org/)
- [General Video Game AI Competition](http://www.gvgai.net/)
- [Angry Birds AI Competition](https://aibirds.org/)
- [The AI Games](http://theaigames.com/)
- [Fighting Game AI Competition](http://www.ice.ci.ritsumei.ac.jp/~ftgaic/)
- [CodeCup](http://www.codecup.nl/intro.php)
- [Student StarCraft AI Tournament](http://sscaitournament.com/)
- [AIIDE StarCraft AI Competition](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/)
- [CIG StarCraft AI Competition](https://sites.google.com/site/starcraftaic/)
- [CodinGame - AI Bot Games](https://www.codingame.com/training/machine-learning)

## Becoming an Open Source Contributor
- [ ] [tensorflow/magenta: Magenta: Music and Art Generation with Machine Intelligence](https://github.com/tensorflow/magenta)
- [ ] [tensorflow/tensorflow: Computation using data flow graphs for scalable machine learning](https://github.com/tensorflow/tensorflow)
- [ ] [cmusatyalab/openface: Face recognition with deep neural networks.](https://github.com/cmusatyalab/openface)
- [ ] [tensorflow/models/syntaxnet: Neural Models of Syntax.](https://github.com/tensorflow/models/tree/master/syntaxnet)

## Podcasts
- ### Podcasts for Beginners:
    - [Talking Machines](http://www.thetalkingmachines.com/)
    - [Linear Digressions](http://lineardigressions.com/)
    - [Data Skeptic](http://dataskeptic.com/)
    - [This Week in Machine Learning & AI](https://twimlai.com/)

- ### "More" advanced podcasts
    - [Partially Derivative](http://partiallyderivative.com/)
    - [O’Reilly Data Show](http://radar.oreilly.com/tag/oreilly-data-show-podcast)
    - [Not So Standard Deviation](https://soundcloud.com/nssd-podcast)

- ### Podcasts to think outside the box:
    - [Data Stories](http://datastori.es/)

## Communities
- Quora
    - [Machine Learning](https://www.quora.com/topic/Machine-Learning)
    - [Statistics](https://www.quora.com/topic/Statistics-academic-discipline)
    - [Data Mining](https://www.quora.com/topic/Data-Mining)

- Reddit
    - [Machine Learning](https://www.reddit.com/r/machinelearning)
    - [Computer Vision](https://www.reddit.com/r/computervision)
    - [Natural Language](https://www.reddit.com/r/languagetechnology)
    - [Data Science](https://www.reddit.com/r/datascience)
    - [Big Data](https://www.reddit.com/r/bigdata)
    - [Statistics](https://www.reddit.com/r/statistics)

- [Data Tau](http://www.datatau.com/)

- [Deep Learning News](http://news.startup.ml/)

- [KDnuggets](http://www.kdnuggets.com/)

## Conferences
- Neural Information Processing Systems ([NIPS](https://nips.cc/))
- IEEE Conference on Computational Intelligence and Games ([CIG](http://www.ieee-cig.org/))
- IEEE International Conference on Machine Learning and Applications ([ICMLA](http://www.icmla-conference.org/))
- International Conference on Machine Learning ([ICML](https://2017.icml.cc/))

## Interview Questions
- [ ] [How To Prepare For A Machine Learning Interview](http://blog.udacity.com/2016/05/prepare-machine-learning-interview.html)
- [ ] [40 Interview Questions asked at Startups in Machine Learning / Data Science](https://www.analyticsvidhya.com/blog/2016/09/40-interview-questions-asked-at-startups-in-machine-learning-data-science)
- [ ] [21 Must-Know Data Science Interview Questions and Answers](http://www.kdnuggets.com/2016/02/21-data-science-interview-questions-answers.html)
- [ ] [Top 50 Machine learning Interview questions & Answers](http://career.guru99.com/top-50-interview-questions-on-machine-learning/)
- [ ] [Machine Learning Engineer interview questions](https://resources.workable.com/machine-learning-engineer-interview-questions)
- [ ] [Popular Machine Learning Interview Questions](http://www.learn4master.com/machine-learning/popular-machine-learning-interview-questions)
- [ ] [What are some common Machine Learning interview questions?](https://www.quora.com/What-are-some-common-Machine-Learning-interview-questions)
- [ ] [What are the best interview questions to evaluate a machine learning researcher?](https://www.quora.com/What-are-the-best-interview-questions-to-evaluate-a-machine-learning-researcher)
- [ ] [Collection of Machine Learning Interview Questions](http://analyticscosm.com/machine-learning-interview-questions-for-data-scientist-interview/)
- [ ] [121 Essential Machine Learning Questions & Answers](https://learn.elitedatascience.com/mlqa-welcome)


## My admired companies
- [ ] [ELSA - Your virtual pronunciation coach](https://www.elsanow.io/home)
