 # Exfiltrate Network Configuration - Linux

A script used to exfiltrate the network configuration on a Linux machine.

**Category**: Exfiltrate, Execution

## Description

A script used to exfiltrate the network configuration on a Linux machine.

Opens a shell, get the network card name, get the network configuration using nmcli, send the result to Dropbox, erase traces.

## Getting Started

### Dependencies

* Internet Connection
* Dropbox Token

### Settings

* Set the Dropbox settings

  ```shell
  # - Set here your Dropbox access TOKEN
  DROPBOX_ACCESS_TOKEN='example'
  # - Set your own Dropbox folder name
  DROPBOX_FOLDER_NAME='example'
  ```

## Credits

<h2 align="center">Aleff</h2>
<div align=center>
<table>
  <tr>
    <td align="center" width="96">
      <a href="https://github.com/aleff-github">
        <img src=https://github.com/aleff-github/aleff-github/blob/main/img/github.png?raw=true width="48" height="48" />
      </a>
      <br>Github
    </td>
    <td align="center" width="96">
      <a href="https://www.linkedin.com/in/alessandro-greco-aka-aleff/">
        <img src=https://github.com/aleff-github/aleff-github/blob/main/img/linkedin.png?raw=true width="48" height="48" />
      </a>
      <br>LinkedIn
    </td>
  </tr>
</table>
</div>