# 2022_01_Independent Capstone Design 
> 동국대학교 컴퓨터공학과 개별연구 1
> 
> *Analysis of Accurate Fire Accident Identification Criteria based on YOLOv5*
<br>

## Team Member
> Ji Hwan Choe , Min Jung Jeon
<br>

## Tool
<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/54761791/161771200-8dabcba3-c09f-4311-a75c-55179a05cde0.png" width = "350" height = "100"/>
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/54761791/161767737-e51233b9-232b-42e2-b0fc-6c02340f29c2.jpg" width="150" height="150"/>
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/54761791/161767484-6b17a39d-b6bf-416a-9b79-b14f49c00187.png" width="150" height="150"/>
    </td>
  </tr>
  <tr>
    <td align="center">
      YOLOv5
    </td>
    <td align="center">
      Roboflow
    </td>
    <td align="center">
      Colab
    </td>
  </tr>
</table>
<br>

## Environment
> python >= 3.7.0 (including pytorch >= 1.7)
<br>

## Process
```
  1. Use yolov5 for tutorial
  2. Data custom (use roboflow or labelimg)
  3. trainning
    # 2-3 repeat
  4. comparison (yolov5 models, epoch, fire size)
```
## Result
![Hnet com-image](https://user-images.githubusercontent.com/54761791/161439236-73a6c044-75f6-462e-8dde-cdaef96fc75c.gif)
![Hnet com-image](https://user-images.githubusercontent.com/54761791/161438769-097e2fea-6f0a-4494-b4dc-e8cba4541bba.gif)
<br><br> 

## Dataset
> Kaggle Fire Dataset:[🔗Link](https://www.kaggle.com/phylake1337/fire-dataset) <br>
> cair/Fire-Detection-Image-Dataset images: [🔗Link](https://github.com/cair/Fire-Detection-Image-Dataset)</br>
> Fire Image Data Set for Dunnings 2018 study-PNG still image set: [🔗Link](https://collections.durham.ac.uk/files/r2d217qp536#.YkMMGShBxD_) </br>
