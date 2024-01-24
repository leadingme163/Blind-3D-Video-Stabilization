# Blind-3D-Video-Stabilization
### Paper Title: 
Blind 3D Video Stabilization with Spatio-Temporally Varying Motion Blur
### Abstract: 
Video stabilization is a challenging task to compensate for the full-frame shake in video acquisition. Existing 3D video stabilization
methods aim at modeling camera perspective projection through either data-driven training or explicit motion estimation. However,
these methods inadequately address the issue of shaky videos with abrupt object movements, resulting in local motion blur in the
direction of the movement. The phenomenon is prevalent in real-world scenarios featuring foreground motion scenes. Combining
stabilization and deblurring methods directly faces challenges in dealing with this situation. The motion blur intensity within the
video undergoes continuous changes, and the direct combination method inadequately utilizes spatio-temporal information, leading to
ineffective compensation for the loss of image consistency over time. In addition, the limited availability of pair-training video data
containing motion blur limits the application of this approach in practice. To alleviate this problem, The Cross-frame-temporal Network
framework proposed by us utilizes cross-frame temporal features to estimate depth maps and camera motion with an un-pretrained
in-test training strategy. In this framework, we propose a Blur Transform Block (BTBlock) designed to adapt to the spatially varying
motion blur. This BTBlock transforms local regions according to the impact of blur intensities to adapt to the effects of non-uniform
motion blur. Furthermore, our Temporal-aware Network (TANet) further suppresses motion blur by leveraging cross-frame temporal
features. Extensive experimental results have demonstrated that our method outperforms state-of-the-art methods.

### Visual Comparison: Our Method vs State-of-the-Art
![]([./Our vs Sota.gif](https://github.com/leadingme163/Blind-3D-Video-Stabilization/blob/main/Our%20vs%20Sota.gif)https://github.com/leadingme163/Blind-3D-Video-Stabilization/blob/main/Our%20vs%20Sota.gif)
