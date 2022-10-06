# Image Recognition
 Based on AliCloud's deep learning technology, image recognition technology can accurately identify the visual content in images, such as thousands of object labels, dozens of common scenes, etc. It provides you with image marking, scene classification, color recognition, style recognition, element recognition and other capabilities. Image recognition technology can be widely used in digital marketing, new retail, advertising design and other industrial scenarios.

## Application Scenario
The application scenarios of image recognition are as follows:

### Intelligent album editing and management

Album images can be classified according to functional tags. For example, scenery photos can be subdivided into sky, beach, sunset, etc.; and personal events can be further grouped into gathering, sports, performance, etc.

### Video scene analysis

Based on a large amount of image recognition data and trained with deep learning algorithms, image recognition technology can accurately identify objects and contents in videos, achieve fully automatic, accurate and fast recognition of videos, improves retrieval efficiency and accuracy, increase view counts and saves labor costs. Besides that, it enables automated video content retrieval, customized recommendation, content retrieval, review and distribution.

# Common Segmentation Tutorial

SegmentCommonImage is an API (Application Program Interface) under the Segmentation service launched by AliCloud Open Platform. You can call this interface to separate the subject object from the background of an image and return to the segmented subject object image.

## Service Activation

Before calling the API, you need to activate the Segmentation service. To segment an image, you need to upload the image to the OSS Bucket in the region of Shanghai to generate an URL link, and transfer the image data to this link. For more information on how to activate the OSS service, please refer to OSS Service Activation.

Below are the steps on how to activate the Segmentation service.

1) Login to AliCloud Visual Intelligence Open Platform.

2) Click **Segmentation** in the **Capability Square** of the top menu.

3) Click **Order Now** on the **Segmentation** page.

Note: For free capabilities during Open Beta, an Order for Free button is shown on the page; for commercially paid capabilities, an Order Now button is shown on the page. You will be charged only after calling.

4) Click **Order Now** after confirming the region and checking the service agreement.

After this step, you will see a prompt-Successful Activation on the page.

Note: After activating the Segmentation service, all APIs under the service can be called directly, and there is no need to activate them separately.

## URL Generation

Assume that you need to segment the image below.

![](SegmentCommonImage.jpg)

1) Login to the OSS Management Console

2) Create a storage space

   When selecting the region for creating Bucket, you need to select the same region as the Segmentation service, East China 2 (Shanghai).

Note: If your OSS is located in a region other than East China 2 (Shanghai), please refer to the guidance of *Generating URL for non-Shanghai OSS users (temporary file transit)*.

3) Upload the above exemplary image to the OSS service

   See Uploading files for details.

4) View the image URL

   From the list of uploaded images, click View the Details and copy the image [URL](https://viapi-test.oss-cn-shanghai.aliyuncs.com/demo-center/imageseg/SegmentCommonImage.jpg)

