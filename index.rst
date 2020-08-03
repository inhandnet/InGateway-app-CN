.. InGateway documentation master file, created by
   sphinx-quickstart on Tue Dec 17 17:24:52 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=====================================
DeviceSupervisor(数据采集与数据上云)
=====================================

----------------------
InGateway文档网站导航
----------------------

.. raw:: html

    <table style="width:100%;">
      <tr>
        <td>
          <div style="display:inline-block;">
            <h3 style="width:auto;">中文文档</h3>
          </div>
          <ul>
          <li><a href="http://manual.ig.inhand.com.cn/zh_CN/latest/">InGateway用户手册</a></li>
          <li><a href="http://sdk.ig.inhand.com.cn/zh_CN/latest/">Python开发者文档</a></li>
          <li><a href="http://app.ig.inhand.com.cn/zh_CN/latest/">DeviceSupervisor(数据采集与数据上云)</a></li>
          <li><a href="http://docker.ig.inhand.com.cn/zh_CN/latest/">Docker用户手册</a></li>
          </ul>
        </td>
        <td>
          <div style="display:inline-block;">
            <h3 style="width:auto;">English Documentation</h3>
          </div>
          <ul>
          <li><a href="http://manual.ig.inhandnetworks.com/en/latest/">InGateway User Manual</a></li>
          <li><a href="http://sdk.ig.inhandnetworks.com/en/latest/">Python Developer Documentation</a></li>
          <li><a href="http://app.ig.inhandnetworks.com/en/latest/">Device Supervisor(Data collecting and uploading)</a></li>
          <li><a href="http://docker.ig.inhandnetworks.com/en/latest/">Docker User Manual</a></li>
          </ul>
        </td>
      </tr>
    </table>

Device Supervisor App为用户提供了便捷且可靠的数据采集、数据二次处理和数据上云等功能，支持ISO on TCP、ModbusRTU等多种工业协议解析。如果您想快速实现多种工业协议的数据采集并在本地预处理设备数据，处理过滤后的数据只需要简单配置后即可对接上传至自建MQTT云平台，那么Device Supervisor将是您理想的选择。

.. toctree::
   :maxdepth: 2
   :caption: 用户手册

   Device-Supervisor用户手册-CN.md
   AliyunIoT-CN.md
