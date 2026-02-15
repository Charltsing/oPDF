# oPDF
  oPDF v2.0 may be the first software to fully showcase the [Wice](https://github.com/aelyo-softworks/Wice) UI framework. The reason why it is said to be the first one is that I submitted nearly 70 issues to make my software UI run and implement the necessary features (large/log text output, high DPI, and AOT publishing). So I 'd like to thank [smourier](https://github.com/smourier) for making the birth of oPDF software possible.

oPDF can parse the internal structure of PDF documents and display and process them as needed. That is to say, it will moderately display the embedded resources such as operators, forms, images, annotations, etc. inside the PDF document to the user. If you can understand these, you can find the watermark or other information that needs to be located. The remaining work is to fill in parameter processing operators or resource objects, also known as removing watermarks.The most important thing is that the pdf document after oPDF processing is **lossless**
    
oPDF can kill eight types of PDF watermarks, including annotation watermark, text watermark, curve watermark, clipping path watermark, artifact watermark, form watermark, image watermark, and pattern watermark.

oPDF can remove editing permissions, flatten forms, eliminate page interactions, and delete digital signatures.

oPDF can freely modify the instruction set of document page content flow and resource content flow, including changing text, color, and position. In other words, it can modify fixed content on the page at once, not just remove watermarks.

![UI](https://github.com/Charltsing/oPDF/blob/main/screenshot1.JPG)

![UI](https://github.com/Charltsing/oPDF/blob/main/screenshot2.JPG)
**Tips:**  
1. Turn on transparency effects in Windows 11, Open Settings → Personalization → Colors, then toggle on Transparency effects.
2. Hover the mouse over the label to see help information.  
    
**I want to declare two prerequisite skills:**  
1. The prerequisite for using oPDF is to understand the PDF operators instructions, all of which are included in the *Introduction*.
2. Before analyzing the watermark, first take a look at the *View resource images* to determine if the watermark is drawn on the image. If so, you will need my another software - [Picture Magick Pro](https://www.cnblogs.com/Charltsing/p/PictureMagick.html).

**The general steps for beginners using oPDF is as follows:**  
1. Drag and drop your PDF document onto the oPDF window.
2. click on the *View resource image* to see if there is a watermark on the image. If not, click on the *Text information* and see if it's a text watermark. If not, click on the *Annotations* and see if it is a annots. If not, click on the *Resources* for in-depth analysis. If nothing can be analyzed, it could be a curve watermark or other type of watermark.
3. You can submit an issue with pdf.zip to me. I will help you analysis the watermarks in your PDF document and remove them if possible.  

User Guide
1. [Remove Text watermarks](https://zhuanlan.zhihu.com/p/1991825405808747927)
2. [Remove Image watermarks](https://zhuanlan.zhihu.com/p/1992482307941107092)
3. [Use wildcard characters](https://zhuanlan.zhihu.com/p/1992485901910159711)
4. [Remove Artifact watermarks](https://zhuanlan.zhihu.com/p/1994421106275267960)
5. [Remove Resource watermarks and Artifact Watermarks by serial number](https://zhuanlan.zhihu.com/p/1995492413335180007)
6. [Remove Annotation watermarks](https://zhuanlan.zhihu.com/p/1996631418231607699)
7. [Remove Curve watermarks (Color section)](https://zhuanlan.zhihu.com/p/2005208521139058108)
8. [Remove Text watermarks (location section)](https://zhuanlan.zhihu.com/p/2005713879133622924)
   
To be continued ...

BTW：
The project includes some PDF samples for beginners to learn how to use oPDF to remove simple watermarks from PDF documents.

**path.pdf**
![UI](https://github.com/Charltsing/oPDF/blob/main/screenshot3.JPG)
