# Awesome Sports Camera Calibration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of resources on Sports Camera Calibration

## Contributing

Feedback and contributions are welcome! To contribute, just create a [pull request](https://github.com/Fallscout/awesome-sports-camera-calibration/pulls).

## Table of Contents
* [Basics](#basics)
* [Papers](#papers)
	* [Homography Estimation for Planar Scenarios](#homography-estimation-for-planar-scenarios)
	* [Dealing with Lens Distortion](#dealing-with-lens-distortion)
	* [Pan-Tilt-Zoom Camera Calibration](#pan-tilt-zoom-ptz-camera-calibration)
	* [Real-time Camera Pose Tracking](#real-time-camera-pose-tracking)
	* [Misc](#real-time-camera-pose-tracking)
* [Datasets](#datasets)

## Basics
* [Multiple view geometry in computer vision](https://cseweb.ucsd.edu/classes/sp13/cse252B-a/HZ2eCh2.pdf) - Hartley, R., & Zisserman, A. (2004)

## Papers

### Homography Estimation for Planar Scenarios
* [Robust incremental rectification of sports video sequences](https://iis.uibk.ac.at/public/papers/Hayet-2004-BMVC.pdf) - Hayet, J., Piater, J., & Verly, J. (2004)
* [Combining line and point correspondences for homography estimation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.186.4525&rep=rep1&type=pdf) - Dubrofsky, E., & Woodham, R. J. (2008)
* [A new normalized method on line-based homography estimation](http://www.nlpr.ia.ac.cn/2008papers/gjkw/gk2.pdf) - Zeng, H., Deng, X., & Hu, Z. (2008)
* [Using line and ellipse features for rectification of broadcast hockey video](https://www.cs.ubc.ca/labs/lci/thesis/ankgupta/gupta11crv.pdf) - Gupta, A., Little, J. J., & Woodham, R. J. (2011)
* [A new accurate and fast homography computation algorithm for sports and traffic video analysis](https://ieeexplore.ieee.org/abstract/document/7990544) - Liu, S., Chen, J., Chang, C., & Ai, Y. (2017)

### Dealing with Lens Distortion
* [An algebraic approach to lens distortion by line rectification](http://ami.dis.ulpgc.es/biblio/bibliography/documentos/AlvarezSendraLensDistortionModel.pdf) - Alvarez, L., & Sendra, R. (2009)
* [Algebraic lens distortion model estimation](https://www.ipol.im/pub/art/2011/ags-alde/article.pdf) - Alvarez, L., Gomez, L. & Sendra, R. (2010)
* [Accurate depth dependent lens distortion models: An Application to Planar View Scenarios](https://www.researchgate.net/publication/220146002_Accurate_Depth_Dependent_Lens_Distortion_Models_An_Application_to_Planar_View_Scenarios) - Alvarez, L., Gómez, L., & Sendra, R. (2011)
* [Radial distortion homography](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Kukelova_Radial_Distortion_Homography_2015_CVPR_paper.pdf) - Kukelova, Z., Heller, J., Bujnak, M., & Pajdla, T. (2015)

### Pan-Tilt-Zoom (PTZ) Camera Calibration
* [Active camera calibration using pan, tilt and roll](http://ami.dis.ulpgc.es/biblio/bibliography/documentos/PTZCalibrationBasuKavita.pdf) Basu, A., & Ravi, K. (1997)
* [Autocalibration from planar scenes](https://hal.inria.fr/inria-00548325/document) - Triggs, B. (1998)
* [Soccer video mosaicking using self-calibration and line tracking](https://ieeexplore.ieee.org/document/905407) - Kim, H., & Hong, K. S. (2000)
* [Automatic camera calibration for image sequences of a football match](https://www.researchgate.net/profile/Flavio_Szenberg/publication/220781377_Automatic_Camera_Calibration_for_Image_Sequences_of_a_Football_Match/links/00b7d51a64210b6959000000.pdf) - Szenberg, F., Carvalho, P., & Gattass, M. (2001)
* [Self-calibration of rotating and zooming cameras](https://www.researchgate.net/profile/Lourdes_Agapito/publication/225865990_Self-Calibration_of_Rotating_and_Zooming_Cameras/links/00b49528a1f46081ad000000.pdf) - Agapito, L. (2001)
* [Acquiring multi-scale images by pan-tilt-zoom control and automatic multi-camera calibration](http://ami.dis.ulpgc.es/biblio/bibliography/documentos/Senior05acquiringmulti-scale.pdf) - Senior, A. W., Hampapur, A., & Lu, M. (2002)
* [The effects of translational misalignment when self-calibration rotating and zooming cameras](https://www.robots.ox.ac.uk/~dwm/Publications/hayman_murray_tpami2003/hayman_murray_tpami2003.pdf) - Hayman, E., & Murray, D. W. (2003)
* [Calibrating pan-tilt cameras in wide-area surveillance networks](https://graphics.stanford.edu/papers/PanTiltCalibration/PanTiltCalib_ICCV2003.pdf) - Davis, J., & Chen, X. (2003)
* [Robust camera calibration for sport videos using court models](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.5.8990&rep=rep1&type=pdf) - Farin, D., Krabbe, S., Effelsberg, W., & de With, P. (2004)
* [Fast camera calibration for the analysis of sport sequences](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.76.6647&rep=rep1&type=pdf) - Farin, D., Han, J., & de With, P. (2005)
* [Automatic camera calibration for images of soccer match](https://waset.org/publications/14049/automatic-camera-calibration-for-images-of-soccer-match-) - Li, Q., & Luo, Y. (2005)
* [An LMI approach for reliable PTZ camera self-calibration](http://ami.dis.ulpgc.es/biblio/bibliography/documentos/PTZCalibrationAnLMIApproachForReliablePTZCameraSelf-Calibration.pdf) - Li, H., & Shen, C. (2006)
* [Online calibration of two zoom-pan-tilt units for planar dynamic events](https://egemenozden.files.wordpress.com/2016/08/dagm06.pdf) - N/A (2006)
* [Pan-tilt-zoom camera calibration and high-resolution mosaic generation](https://snsinha.github.io/pdfs/SinhaCVIU2006.pdf) - Sinha, S. N., & Pollefeys, M. (2006)
* [On-line rectification of sport sequences with moving cameras](https://pdfs.semanticscholar.org/dfde/125541628d98e65284ae1d98a85e7ab8f289.pdf) - Hayet, J., & Piater, J. (2007)
* [Continual and robust estimation of camera parameters in broadcasted sports games](https://mediatum.ub.tum.de/doc/649729/649729.pdf) - Gedikli, S. (2009)
* [Camera pose estimation in soccer scenes based on vanishing points](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1005.8778&rep=rep1&type=pdf) - Babaee-Kashany, V., & Pourreza, H. R. (2010)
* [Exploiting distinctive visual landmark maps in pan-tilt-zoom camera networks](https://www.sciencedirect.com/science/article/pii/S1077314210000305) - Del Bimbo, A., Dini, F., Lisanti, G., & Pernici, F. (2010)
* [Automatic line mark recognition and its application in camera calibration in soccer video](https://ieeexplore.ieee.org/document/6012137) - Bu, J., Lao, S., & Bai, L. (2011)
* [Robust multi-view camera calibration for wide-baseline camera networks](http://www-oldurls.inf.ethz.ch/personal/marc.pollefeys/pubs/PuweinWACV11.pdf) - Puwein, J., Ziegler, R., Vogel, J., & Pollefeys, M. (2011)
* [PTZ camera network calibration from moving people in sports broadcasts](http://www-oldurls.inf.ethz.ch/personal/marc.pollefeys/pubs/PuweinWACV12.pdf) - Puwein, J., & Ziegler, R. (2012)
* [Keeping a pan-tilt-zoom camera calibrated](https://www.researchgate.net/publication/240308786_Keeping_a_Pan-Tilt-Zoom_Camera_Calibrated) - Wu, Z., & Radke, R. (2013)
* [Camera calibration in sport event scenarios](http://clok.uclan.ac.uk/18033/1/18033-Camera_calibration_in_sport_event_scenarios.pdf) - Aleman-Flores, M., Alvarez, L., Gomez, L., Henriquez Castellano, P., & Mazorra, L. (2014)
* [Method for pan-tilt camera calibration using single control point](https://www.researchgate.net/publication/269935858_Method_for_pan-tilt_camera_calibration_using_single_control_point) - Li, Y., Zhang, J., Hu, W., & Tian, J. (2015)
* [Court reconstruction for camera calibration in broadcast basketball videos](https://ieeexplore.ieee.org/document/7118240) - Wen, P., Cheng, W., Wang, Y., Chu, H., Tang, N. C., & Liao, H. M. (2016)
* [Deep regression for monocular camera-based 6-DoF global localization in outdoor environments](http://ais.informatik.uni-freiburg.de/publications/papers/naseer17iros.pdf) - Nascer, T., & Burgard, W. (2017)
* [Sports field localization via deep structured models](http://www.cs.toronto.edu/~namdar/pdfs/sports_cvpr_2017.pdf) - [[Code](https://nhoma.github.io/papers/sports_soccer_code.zip)] - Homayounfar, N., Fidler, S., & Urtasun, R. (2017)
* [A two-point method for PTZ camera calibration in sports](https://arxiv.org/pdf/1801.09005.pdf) - Chen, J., Zhu, F., & Little, J. J. (2018)
* [Calibrating cameras in poor-conditioned pitch-based sports games](http://150.162.46.34:8080/icassp2018/ICASSP18_USB/pdfs/0001902.pdf) - Zeng, R., Lakemond, R., Denman, S., Sridharan, S., Fookes, C., & Morgan, S. (2018)
* [Sports Camera Calibration via Synthetic Data](http://openaccess.thecvf.com/content_CVPRW_2019/papers/CVSports/Chen_Sports_Camera_Calibration_via_Synthetic_Data_CVPRW_2019_paper.pdf) - [[Code Part1](https://github.com/lood339/SCCvSD)/[Code Part 2](https://github.com/lood339/pytorch-two-GAN)] - Chen, J., & Little, J. J. (2019)

### Real-time Camera Pose Tracking
* [A soccer field tracking method with wire frame model from TV images](https://ieeexplore.ieee.org/document/1421382) - Watanabe, T., Haseyama, M., & Kitajima, H. (2004)
* [Real-time camera tracking using sports pitch markings](https://www.researchgate.net/publication/220243595_Real-time_camera_tracking_using_sports_pitch_markings) - Thomas, G. (2007)
* [Realtime camera motion tracking in planar view scenarios](https://www.researchgate.net/publication/237842364_Real-Time_Camera_Motion_Tracking_in_Planar_View_Scenarios) - Alvarez, L., Gomez, L., Henriquez, P., & Sánchez, J. (2013)
* [PoseNet: A convolutional network for real-time 6-DOF camera relocalization](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf) - Kendall, A., Grimes, M., & Cipolla, R. (2015)
* [Continuous localization and mapping of pan-tilt-zoom camera for wide area tracking](https://arxiv.org/pdf/1401.6606.pdf) - Lisanti, G., Masi, I., Pernici, F., & Del Bimbo, A. (2015)
* [Pan-tilt-zoom SLAM for Sports Videos](https://bmvc2019.org/wp-content/uploads/papers/0329-paper.pdf) - [[Code](https://github.com/lulufa390/Pan-tilt-zoom-SLAM)] - Lu, J., Chen, J., & Little, J. J. (2019)
* [Real-time camera pose estimation for sports fields](https://arxiv.org/pdf/2003.14109.pdf) - Citraro, L., Marquez-Neila, P., Savare, S., Jayaram, V., Dubout, C., Renault, F., hasfura, A., Ben Shitrit, H., & Fua, P. (2020)
* [A robust and efficient framework for sports-field registration](https://www.amazon.science/publications/a-robust-and-efficient-framework-for-sports-field-registration) - Nie, X., Chen, S., & Hamid, R. (2021)

### Misc
* [Tracking players and a ball in video image sequence and estimating camera parameters for 3D interpretation of soccer games](http://www.aisl.cs.tut.ac.jp/~jun/pdffiles/yamada-icpr2002.pdf) - Yamada, A., Shirai, Y., & Miura, J. (2002)
* [Tracking soccer ball in TV broadcast video](https://www.researchgate.net/publication/221356623_Tracking_Soccer_Ball_in_TV_Broadcast_Video) - Choi, K., & Seo, Y. (2005)
* [A new method to calculate the camera focusing area and player position on play field in soccer video](https://www.researchgate.net/publication/228391113_A_new_method_to_calculate_the_camera_focusing_area_and_player_position_on_playfield_in_soccer_video) - Liu, Y., Huang, Q., Ye, Q., & Gao, W. (2005)
* [Automatic production system of soccer sports video by digital camera work based on situation recognition](https://www.researchgate.net/publication/221558506_Automatic_Production_System_of_Soccer_Sports_Video_by_Digital_Camera_Work_Based_on_Situation_Recognition) - Ariki, Y., Kubota, S., & Kumano, M. (2006)
* [Extracting 3D information from broadcast soccer video](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.89.870&rep=rep1&type=pdf) - Liu, Y., Liang, D., Huang, Q., & Gao, W. (2006)
* [Fast arc detection algorithm for play field registration in soccer video mining](https://ieeexplore.ieee.org/document/4274696) - Wang, F., Sun, L., Yang, B., & Yang, S. (2006)
* [Motion fields to predict play evolution in dynamic sport scenes](https://www.cc.gatech.edu/cpl/projects/playevolution/cvpr2010-pe.pdf) - Kim, K., Grundmann, M., Shamir, A., Matthews, I., Hodgins, J., & Essa, I. (2010)
* [Automatic player labeling, tracking and field registration and trajectory mapping in broadcast soccer video](http://www.bmva.org/bmvc/2007/papers/paper-70.pdf) - Liu, J., Tong, X., Li, W., Wang, T., Zhang, Y., Wang, H., Yang, B., Sun, L., & Yang, S.(2011)
* [An algorithm for highlights identification and summarization of broadcast soccer videos](https://link.springer.com/content/pdf/10.1007/978-3-642-33275-3_106.pdf) - Junior, W. A. G., & Borges, D. L. (2012)
* [Automatic soccer video analysis and summarization](https://www.researchgate.net/publication/5613899_Automatic_Soccer_Video_Analysis_and_Summarization) - Ekin, A., Tekalp, A. M., & Mehrotra, R. (2003)
* [Robust video registration applied to field-sports video analysis](https://ivul.kaust.edu.sa/Documents/Publications/2012/Robust%20Video%20Registration%20Applied%20to%20Field-Sports%20Video%20Analysis.pdf) - Ghanem, B., Zhang, T., & Ahuja, N. (2012)
* [Automated top view registration of broadcast football videos](https://arxiv.org/pdf/1703.01437.pdf) - Sharma, R. A., Bhat, B., Gandhi, V., & Jawahar, C. V. (2017)
* [Soccer on your tabletop](https://grail.cs.washington.edu/projects/soccer/soccer_on_your_tabletop.pdf) - Rematas, K., Kemelmacher-Shlizerman, I., Curless, B., & Seitz, S. (2018)
* [Optimizing Through Learned Errors for Accurate Sports Field Registration](https://arxiv.org/pdf/1909.08034.pdf) [[Code](https://github.com/vcg-uvic/sportsfield_release)] - Jiang, W., Gamboa Higuera, J. C., Angles, B., Sun, W., Javan, M., & Moo Yi, K. (2020)
* [SFLNet: Direct Sports Field Localization via CNN-Based Regression](https://link.springer.com/chapter/10.1007/978-3-030-41404-7_48) - Tarashima, S. (2020)

## Datasets
* [World Cup 2014 Dataset](http://www.cs.toronto.edu/~namdar/data/soccer_data.tar.gz) - Homayounfar, N., Fidler, S., & Urtasun, R. (2017)
* [Highlights Dataset](https://www.cs.ubc.ca/~jhchen14/ccnn_player_detection/) - Lu, K., Chen, J., Little, J. J., & He, H. (2017)
