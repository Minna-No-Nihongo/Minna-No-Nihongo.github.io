# Minna-No-Nihongo.github.io
About me
<html>
Hello World  
  <table style="border:inherit">
            <tr>
                <th>Employee ID</th>
                <th>Name</th>
                <th>Email</th>
                <th>Contact No</th>
                <th>Created_Date</th>
                <th>Actions</th>
            </tr>
            @foreach (var emp in Model)
            {
                <tr>
                    <td>1101</td>
                    <td>Shivam</td>
                    <td>shivam@theitmaniac.com</td>
                    <td>7666762829</td>
                    <td>22/05/2023</td>
                    <td>
                        Edit
                        |
                        Delete
                    </td>
                </tr>
            }
        </table>
</html
