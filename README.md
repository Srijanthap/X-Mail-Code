# X-Mail-Code
It is just the demo of WPFfdesign
<Page
    x:Class="App1.MainPage"
    xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
    xmlns:local="using:App1"
    xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
    xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
    mc:Ignorable="d"
    Background="{ThemeResource ApplicationPageBackgroundThemeBrush}">


    <Grid>
        <Button x:Name="button4" Content="Remove Country" Margin="57,662,0,0" VerticalAlignment="Top" Height="66" Width="275" Click="RemoveCountry_Click" Background="#330A291F" FontWeight="Bold" FontStyle="Italic" FontSize="20"/>
        <Button x:Name="button5" Content="Remove State" Margin="375,662,0,0" VerticalAlignment="Top" Height="66" Width="275" Click="RemoveState_Click" Background="#33BD14A7" FontSize="20" FontWeight="Bold"/>
        <Button x:Name="button6" Content="Show Details" Margin="699,662,0,0" VerticalAlignment="Top" Height="66" Width="275" Click="ShowDetails_Click" Background="#334D14BD" FontSize="20" FontWeight="Bold"/>

        <TextBox x:Name="textbox2" HorizontalAlignment="Left" Margin="280,71,0,0" TextWrapping="Wrap" Text="" VerticalAlignment="Top" Height="77" Width="370" FontSize="20" FontWeight="Bold" FontStyle="Italic"/>
        <TextBox x:Name="textbox1" HorizontalAlignment="Left" Margin="280,153,0,0" TextWrapping="Wrap" Text="" VerticalAlignment="Top" Height="77" Width="370" FontSize="20" FontWeight="Bold" FontStyle="Italic"/>
        <TextBox x:Name="textbox3" HorizontalAlignment="Left" Margin="280,235,0,0" TextWrapping="Wrap" Text="" VerticalAlignment="Top" Height="77" Width="370" FontSize="20" FontWeight="Bold" FontStyle="Italic"/>

        <TextBlock x:Name="textblock1" HorizontalAlignment="Left" Margin="63,83,0,0" TextWrapping="Wrap" Text="Name:" VerticalAlignment="Top" Height="68" Width="180" FontWeight="Bold" FontStyle="Italic" FontSize="20"/>
        <TextBlock x:Name="textblock2" HorizontalAlignment="Left" Margin="57,153,0,0" TextWrapping="Wrap" Text="Country Name:" VerticalAlignment="Top" Height="68" Width="180" FontWeight="Bold" FontStyle="Italic" FontSize="20"/>
        <TextBlock x:Name="textblock3" HorizontalAlignment="Left" Margin="63,235,0,0" TextWrapping="Wrap" Text="Country State:" VerticalAlignment="Top" Height="68" Width="180" FontWeight="Bold" FontStyle="Italic" FontSize="20"/>

        <CheckBox x:Name="chkEmail" Content="E-mail" Margin="57,411,0,0" VerticalAlignment="Top" Height="42" Width="110" FontSize="20" RenderTransformOrigin="0.187,0.488" FontWeight="Bold" FontStyle="Italic"/>
        <CheckBox x:Name="chkPostMail" Content="Post Mail" Margin="56,467,0,0" Height="42" Width="126" FontSize="20" FontWeight="Bold" FontStyle="Italic" VerticalAlignment="Top"/>

        <RadioButton x:Name="radioMale" Content="Male" Margin="280,406,0,0" VerticalAlignment="Top" Height="62" Width="185" FontSize="20" FontWeight="Bold" FontStyle="Italic" GroupName="Gender"/>
        <RadioButton x:Name="radioFemale" Content="Female" Margin="280,467,0,0" VerticalAlignment="Top" Height="62" Width="185" FontSize="20" FontWeight="Bold" FontStyle="Italic" GroupName="Gender"/>

        <ListBox x:Name="listBoxSports" Margin="934,71,179,517" Background="#FF9EC0B0">
            <ListBoxItem Content="Volleyball"></ListBoxItem>
            <ListBoxItem Content="Cricket"></ListBoxItem>
            <ListBoxItem Content="Badminton"></ListBoxItem>
            <ListBoxItem Content="Football"></ListBoxItem>
        </ListBox>

        <ComboBox x:Name="comboBoxCourses" Margin="996,530,0,0" Width="326" Height="50">
            <ComboBoxItem Content="Computer Programming"></ComboBoxItem>
            <ComboBoxItem Content="Business"></ComboBoxItem>
            <ComboBoxItem Content="Hospitality"></ComboBoxItem>
            <ComboBoxItem Content="Hotel Management"></ComboBoxItem>
        </ComboBox>
    </Grid>
</Page>
