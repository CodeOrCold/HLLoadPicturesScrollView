# HLLoadPicturesScrollView

1.创建

HLScrollView scrollView = [HLScrollView cycleScrollViewWithFrame:CGRectMake(0, 0, self.view.bounds.size.width, self.view.bounds.size.height0.4) delegate:self placeholderImage:[UIImage imageNamed:@"jobs.jpg"]];

2.设置图片url

scrollView.imageURLStringsGroup = [HLData returnPicturesArray];

3.设置标题内容

scrollView.titlesGroup = [HLData retur
