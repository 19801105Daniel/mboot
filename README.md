# mboot
Tool for Intel OSIP header Android﻿<?xml version="1.0" encoding="utf-8"?>
 <AppUpdate>
   <configuration>
     <!--
     updateApp 为"true"时升级界面程序，
     cover 为"true"时不删除之前的目标文件夹，
     force 为“true”时，已存在有程序直接替换
     -->
     <Set updateApp="true" cover="false" force="true" ></Set>
     <!--SrcPath 拷贝源文件 DestPath为目标文件
     拷贝时会删除目标文件
     目录后请不要加斜杠，否则会有错误
     -->
     <SrcPath>\Storage Card\S100PROGRAM</SrcPath>
     <DestPath>\SDMMCDisk\S100PROGRAM</DestPath>
     <APPName>Platform.exe</APPName>
     
     <!--屏幕大小：0 为 6.2寸； 1 为 7寸； 2 为 8寸；3 为 9寸；4 为 4.3寸；5 为 5寸；6 为 6.95寸；7 为 9寸宽屏-->
     <LCD id="1">
       <Calibration id="0">2010,1990 3547,577 3549,3378 465,3406 476,600</Calibration>
       <Calibration id="1">2103,2000 3618,591 3607,3375 583,3413 579,625</Calibration>
       <Calibration id="2">2011,2032 3529,636 3470,3337 475,3436 521,708</Calibration>
       <Calibration id="3">2103,2000 3618,591 3607,3375 583,3413 579,625</Calibration>
       <Calibration id="4">2103,2000 3618,591 3607,3375 583,3413 579,625</Calibration>
       <Calibration id="5">2061,2062 3459,3606 648,3606 668,528 3442,538</Calibration>
       <Calibration id="6">2103,2000 3618,591 3607,3375 583,3413 579,625</Calibration>
       <Calibration id="7">2103,2000 3618,591 3607,3375 583,3413 579,625</Calibration>
     </LCD>
     
     <!--run 为 "true"时,运行校准程序-->
     <TouchExe run="false">\Storage Card\S100PROGRAM\TouchCalibration.exe</TouchExe>
     
     <!--run 为 "true"时,运行MCU升级程序-->
     <McuExe run="true" mcu="true" flash="true">\SDMMCDisk\S100PROGRAM\UpdateMCU_Auto.exe</McuExe>
     
     <!--run 为 "true"时，运行蓝牙升级程序-->
     <BTExe run="false">\Storage Card\BTUpdate\WinCeDFU.exe</BTExe>
     
   </configuration>
 </AppUpdate> image format
Nowy
