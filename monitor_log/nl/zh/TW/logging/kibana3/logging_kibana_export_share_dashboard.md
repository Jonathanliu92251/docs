---

copyright:
  years: 2016, 2017
lastupdated: "2017-02-03"

---

<!-- Common attributes used in the template are defined as follows: -->
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}


#匯出及共用 Kibana 儀表板
<!-- for example, Uploading your data -->
{: #exporting_sharing_kibana_dash}
<!-- Provide an appropriate ID above -->

<!-- The short description section should include a sentence describing why this task is needed. For search engine optimization, include the service long name and "Bluemix". For example: -->

將儀表板綱目匯出成 JSON 檔案，或是共用日誌資料的自訂 Kibana 儀表板 URL。
{:shortdesc}

<!-- Include a sentence to briefly introduce the steps/subtopics. Example: -->
Kibana 可讓您將儀表板匯出成 JSON 檔案，或是共用儀表板的 URL，以與其他利害關係人分工合作。

完成下列作業，以將 Kibana 儀表板匯出成 JSON 檔案：

1. 按一下**儲存**圖示 ![儲存圖示](images/logging_save.jpg)，然後按一下**進階** **>** **匯出綱目**。

    ![將儀表板匯出成 JSON 檔案](images/logging_export_json.jpg)

2. 為 JSON 檔案選擇有意義的名稱，然後按一下**儲存**。有了這個 JSON 檔案的任何使用者，都可以在其 Kibana 儀表板中開啟檔案。 

完成下列作業，以建立及共用 Kibana 儀表板的 URL：

1. 在 Kibana 儀表板上，按一下**資料夾**圖示 ![資料夾圖示](images/logging_folder.jpg)，以顯示列出所有最近儀表板的功能表。除了您命名儲存的儀表板之外，此功能表也會根據下列格式，列出未命名的儀表板：*ALCH_TENANT_ID_application_id*。 

    ![儀表板清單](images/logging_list_of_dashboards.jpg)

2. 對於您要共用的儀表板，按一下**共用**圖示 ![共用圖示](images/logging_create_url.jpg)。即會建立並顯示可共用的 URL。 

    ![可共用的 URL 窗格](images/logging_shareable_link_popup.jpg)

    複製 URL，以與其他使用者共用您的儀表板。按一下**關閉**，回到您的儀表板。
