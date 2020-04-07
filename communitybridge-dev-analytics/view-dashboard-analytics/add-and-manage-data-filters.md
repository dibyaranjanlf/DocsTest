# Add and Manage Data Filters

On a dashboard, you can add a filter for the data results and display only the data that contain a particular value. You can also create negative filters that exclude data that contain the specified value. Filtering makes it easier for you to focus on specific information on a dashboard. The applied filters are shown in the query bar. Negative filters start with NOT in red.

After you add a filter, you can manage it by applying quick actions on the filter label such as excluding matches, and editing or removing the filter.

* * 
## Add a Filter <a id="AddandManageDataFilters-AddaFilter"></a>

**Do these steps:**

1. On a dashboard, click + **Add filter**. The **EDIT FILTER** dialog appears.
2. Click in the **Filter** field and:
   * Select a filter from the **Field** drop-down list. ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3ja1prQbafWjzfD_6S%2Fadd%20filter.png?alt=media&token=d013d8ef-4ce0-48e3-b908-08844a733ac9)
   * Select an operator from the **Operato**r drop-down list
   * Type or select a filter value in the **Value** field. **Note:** You can turn on the **Create** **Custom label?** key to open **Custom label** field that lets you enter a label value that identifies your filter subject.
3. Click **Edit as Query DSL** to build a filter using Elastic search Query DSL. You can create positive and negative operators and filter on whether or not a field is present. ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3jaaSMXVezbvf30DKO%2Fedit%20as%20query%20DSL.png?alt=media&token=893b1259-e74a-4b7d-9c07-df88b6ecfcc2)
4. Click **Save**. The filter label appears in the query bar.
5. \(Optional\) Click ![](https://docs.linuxfoundation.org/download/thumbnails/18088146/filter%20option%20button.PNG?version=1&modificationDate=1583236994062&api=v2) to show the **CHANGE ALL FILTERS** options as shown in the following example:
   * **Enable all** enables all the disabled filters.
   * **Disable** **all** disables the filters without removing them. Strike-through indicates that filters are disabled.
   * **Pin all** pins the filters. Pinned filters persist when you switch contexts. For example, you can pin a filter in one dashboard and it remains in place when you switch to another dashboard. A filter is based on a particular index field—if the indices being searched do not contain the field in a pinned filter, it has no effect.
   * **Unpin all** disables all pinned filters.
   * **Invert inclusion** switches the positive filters to negative filters and vice-versa.
   * **Invert enabled/disabled** switches the enabled filters to disabled filters and vice-versa.
   * **Remove all** removes all the filters from the action bar.

## Edit and Manage a Filter <a id="AddandManageDataFilters-EditandManageaFilter"></a>

The Edit filter option lets you manually update a filter and specify a label for it.

**To edit a filter:**

1. Click the filter that you want to edit and click **Edit filter**: ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3jcFW_oaE4Gr34w1on%2Fedit%20filter.png?alt=media&token=6982d297-2125-48b4-ae66-dbbd96fb6cff) ![](https://docs.linuxfoundation.org/download/attachments/18088146/edit%20filter.PNG?version=1&modificationDate=1583236994028&api=v2) The Edit filter dialog appears. ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3jc0_CkLixnoWVQ4La%2Fedit%20filter%20values.png?alt=media&token=63b4f7db-fb5c-4a47-a4de-251aa8415856)
2. Edit the filter by clicking **Edit as Query DSL** and following the instructions to edit a filter. ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3jbpSyo5AevpiyW5Er%2Fedit%20filter%20as%20query%20DSL.png?alt=media&token=4be28cf8-e0c2-43de-9574-cd977a97fa26)
3. Click **Save**.

**To manage a filter:**

1. Click the filter that you want to manage, and select any of the **action buttons** to manage a filter:
   * **Pin across all apps** pins a filter across all applications in one dashboard. It remains in place when you switch to another dashboard. A filter is based on a particular index field—if the indices being searched do not contain the field in a pinned filter, it has no effect.
   * **Edit filter** opens the Edit filter dialog.
   * **Exclude results** excludes items that match the specified field value. **Include results** option shows when you click Exclude results.
   * **Temporarily disable** disables the filter without removing it. Strike-through indicates that a filter is disabled. **Re-enable** option shows when you click Temporarily disable.
   * **Delete** removes the filter. **Note:** You can click **×** next to a filter to delete it. ![](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-M2DCN9UgoRgMEkgnLyP%2F-M3jTvKvmK5UBxI9q73S%2F-M3jcey-8a2JZQX7NFc_%2Fdelete%20filter.png?alt=media&token=caff7d13-ae37-466c-8d48-beb0ddbfbdae)

​

