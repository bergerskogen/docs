# Delete Objects

<span style="FONT-WEIGHT: normal">Use this effect to delete objects from a data source.

<span style="FONT-WEIGHT: normal">For information on committing changes, adjusting transaction timeouts, running with elevated privileges, and supressing user notifications, see <span style="FONT-WEIGHT: normal">[Scope](../blocks/scope.md)<span style="FONT-WEIGHT: normal">.

**** **Delete Objects** 

1.  In the **Name** box, optionally enter a name. The name is displayed in the action tree, if a name is not entered, a summary of the effect is displayed.
2.  In the **Description** box, optionally enter a description.
3.  In the **Data Source** box, select the data source you want to delete objects from.
4.  Click to clear the **Restrict to objects in data source** <span style="FONT-WEIGHT: normal">check box, if the delete operation should not be restricted to objects in the data source. In some cases you are allowed to delete objects which not are present in your data source. For example, clear temporary data or large volumes of data. Then you do not want load the objects into a data source since this would require a lot of resources. To speed up performance, no integrity check is performed when objects are deleted.  
    This option is only available for data sources which satisfied the following requirements:  
    b " The data source has to be of type object  
    b " The data source cannot be composed of other data sources  
    b " The data source is not restricted by security permissions  
    b " The data source cannot be part of another data source restricted by security permissions  
    b " Audit trails not logged in the Event History for the data source
5.  If you want to delete all objects, click **Delete all object**. This option is only available if the delete operation is restricted to objects in the data source. If you do not want to delete all objects in the data source, click **Delete objects which meet the condition** and click **Change** to specify a [condition](../../../../common-concepts/conditions.md).

**Delete Account Session History**

1.  <span style="FONT-WEIGHT: normal">I<span style="FONT-WEIGHT: normal">n the **Data Source** <span style="FONT-WEIGHT: normal">box, select **Account Session History**<span style="FONT-WEIGHT: normal">.
2.  <span style="FONT-WEIGHT: normal">The **Delete objects which meet the condition** <span style="FONT-WEIGHT: normal">option is automaticllay selected.
3.  <span style="FONT-WEIGHT: normal">To specify the condion, click **Change**<span style="FONT-WEIGHT: normal">.
4.  <span style="FONT-WEIGHT: normal">To delete history for all accounts<span style="FONT-WEIGHT: normal">, click **All Accounts.**
5.  **T**<span style="FONT-WEIGHT: normal">o delete history for specific accounts, click **Selected Accounts,** <span style="FONT-WEIGHT: normal">and then select individual accounts.
6.  <span style="FONT-WEIGHT: normal">In the **Older Than** <span style="FONT-WEIGHT: normal">boxes enter a number and select a period to specify which period to delete account session history for.

**Delete Agent Execution History**

 <span style="FONT-WEIGHT: normal">1.  In the **Data Source** box, select **Agent Execution History**.
2.  The **Delete objects which meet the condition** option is automaticllay selected.
3.  To specify the condion, click **Change**.
4.  To delete history for all agents, click **All Agents.**
5.  **T**o delete history for specific agents, click **Selected Agents,** and then select individual agents.
6.  In the **Older Than** boxes enter a number and select a period to specify which period to delete agent execution history for.

**Delete Event History** 

1.  In the **Data Source** box, select **Event History**.
2.  <span style="FONT-WEIGHT: normal">The **Delete objects which meet the condition** <span style="FONT-WEIGHT: normal">option is automaticllay selected.
3.  <span style="FONT-WEIGHT: normal">To specify the condion, click **Change**<span style="FONT-WEIGHT: normal">.
4.  <span style="FONT-WEIGHT: normal">In the **Object Class** <span style="FONT-WEIGHT: normal"><span style="FONT-WEIGHT: normal">box, select the object class to delete event history for.
5.  <span style="FONT-WEIGHT: normal">The **Delete objects which meet the condition** <span style="FONT-WEIGHT: normal">option is automaticllay selected.
6.  <span style="FONT-WEIGHT: normal">To specify the condion, click **Change**<span style="FONT-WEIGHT: normal">.
7.  <span style="FONT-WEIGHT: normal">In the **Object Class** <span style="FONT-WEIGHT: normal"><span style="FONT-WEIGHT: normal">box, select the object class to delete event history for.
8.  Click **All Objects** to delete event history for all the objects in the selected object class. For built in object classes e.g. Agent and Web, you can click **Selected Objects** for selecting individual agent, web services etc. if you want to target the delete operation more finely.
9.  In the **Event** box, select one or more of the event types you want to delete.
10.  In the **Older Than** boxes, enter a number and select a period to specify period to delete event history for.

See Also

*   [Deleting Event History and Account Session History](../../../../../guidelines-and-best-practices/deleting-event-history-and-account-session-history.md)