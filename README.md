# ShimmysAdminTools
Unturned 的管理工具包，包括飞行和 Noclip。
功能优化和中文化翻译

# Demo Video
Heres a very out-dated demo video. I'll get around to making a proper one eventually.


# 命令
<table>
    <tr>
        <th>命令</th>
        <th>描述</th>
    </tr>
    <tr>
        <td>AFly</td>
        <td>切换飞行</td>
    </tr>
    <tr>
        <td>AFlySpeed [速度]</td>
        <td>更改/重置飞行速度</td>
    </tr>
    <tr>
        <td>AFlyVSpeed [速度]</td>
        <td>更改/重置垂直飞行速度</td>
    </tr>
    <tr>
        <td>Noclip</td>
        <td>切换穿墙模式</td>
    </tr>
    <tr>
        <td>CheckBedOwner</td>
        <td>检查当前查看的床的拥有者</td>
    </tr>
    <tr>
        <td>DisableVehicleAccess [玩家]</td>
        <td>禁用/启用玩家进入和使用载具的能力</td>
    </tr>
    <tr>
        <td>ForceDismount [玩家]</td>
        <td>强制玩家下车</td>
    </tr>
    <tr>
        <td>GotoBed [名字/ID]</td>
        <td>传送到另一个玩家的床</td>
    </tr>
    <tr>
        <td>Marker [标记名称]</td>
        <td>在当前位置放置标记</td>
    </tr>
    <tr>
        <td>GotoMarker [标记名称]</td>
        <td>传送到先前设置的标记</td>
    </tr>
    <tr>
        <td>PointTool [工具]</td>
        <td>切换/更改当前的指向工具（见下文）</td>
    </tr>
    <tr>
        <td>MapJump</td>
        <td>切换地图/标记跳跃（在新标记上传送）。</td>
    </tr>
     <tr>
        <td>SalvageTime [秒]</td>
        <td>更改需要打捞物品的时间</td>
    </tr>
     <tr>
        <td>CommandSpy</td>
        <td>切换全局命令监视。</td>
    </tr>
     <tr>
        <td>CommandSpy [玩家]</td>
        <td>切换对玩家的命令监视。</td>
    </tr>
     <tr>
        <td>SetFireMode [模式]</td>
        <td>强制更改枪的射击模式（例如，全自动灰熊）。</td>
    </tr>
     <tr>
        <td>UnlockFireModes</td>
        <td>允许通过热键循环所有射击模式。</td>
    </tr>
     <tr>
        <td>Attachment [附件名称/ID]</td>
        <td>强制为武器添加附件。</td>
    </tr>
     <tr>
        <td>Attachment [弹匣名称/ID]</td>
        <td>强制为武器提供任何弹匣/弹药夹。</td>
    </tr>
     <tr>
        <td>UnlimitedAmmo</td>
        <td>启用/禁用无限弹药。</td>
    </tr>
     <tr>
        <td>UnlimitedAmmo [最大弹药覆盖]</td>
        <td>启用无限弹药，覆盖枪的最大弹药。</td>
    </tr>
     <tr>
        <td>Exec [玩家] [命令/消息]</td>
        <td>类似于/sudo，但目标玩家不需要权限即可执行命令。</td>
    </tr>
    <tr>
        <td>ExecAll [命令/消息]</td>
        <td>与/Exec相同，但针对所有玩家。</td>
    </tr>
    <tr>
        <td>WipePlayerBuildings [玩家/玩家ID]</td>
        <td>清除目标玩家放置的所有建筑/障碍物。</td>
    </tr>
    <tr>
        <td>WipePlayerBuildings [玩家/玩家ID] [建筑/障碍物ID]</td>
        <td>清除目标玩家放置的特定建筑/障碍物。</td>
    </tr>
    <tr>
        <td>Ascend [距离]</td>
        <td>向上传送指定距离。</td>
    </tr>
    <tr>
        <td>Descend [距离]</td>
        <td>向下传送指定距离。</td>
    </tr>
    <tr>
        <td>PlaceObject [障碍物/建筑名称/ID]</td>
        <td>在当前位置创建并放置指定的障碍物/建筑。</td>
    </tr>
    <tr>
        <td>ClearInventory</td>
        <td>清空你的库存</td>
    </tr>
</table>

## 指向工具
指向工具是一套小工具，通过打击/手势触发。这些工具将目标锁定在你当前查看的位置/物体上。

<table>
    <tr>
        <td>工具</td>
        <td>描述</td>
    </tr>
    <tr>
        <td>Destroy</td>
        <td>摧毁你当前查看的物体。适用于障碍物、建筑物和载具。</td>
    </tr>
    <tr>
        <td>Kill</td>
        <td>杀死你当前查看的玩家/动物/僵尸。将玩家变成金色。</td>
    </tr>
    <tr>
        <td>Jump</td>
        <td>传送到你当前查看的位置。<br>
            <ul>
                <li>左拳 - 找到你打击附近的最高点，例如打击旗杆，传送到其顶部。</li>
                <li>右拳 - 传送到你当前查看的物体内部，允许你穿墙。</li>
                <li>指向 - 直接传送到你查看的位置，但不进入物体内部。</li>
                </ul>
            你也可以向天空打击以传送到天空盒，然后向下打击到地图上的任何地方。这允许你快速且高精度地传送到任何地方。
        </td>
    </tr>
    <tr>
        <td>Utility</td>
        <td>一套小工具<br>
            <ul>
                <li>引爆炸药</li>
                <li>打开/关闭门（即使你不拥有它们）</li>
                <li>检查床的拥有者（与/CheckBedOwner相同）</li>
                <li>打开储物柜（从任何距离，即使你不拥有它们）</li>
            </ul>
        工具仍在添加中。
    </tr>
    <tr>
        <td>Repair</td>
        <td>修理障碍物、建筑物、载具和载具轮胎。</td>
    </tr>
    <tr>
        <td>CheckOwner</td>
        <td>显示建筑物、障碍物和锁定载具的拥有者以及玩家的组别。</td>
    </tr>
</table>

更多的'指向工具'仍在添加中。这不是最终版本。

# 权限

<table>
    <tr>
        <td>权限</td>
        <td>描述</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.Flight</td>
        <td>提供所有飞行命令的访问权限，包括/Afly, /AflySpeed 和 /AflyVSpeed</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.Flight.MaxSpeed.X</td>
        <td>设置最大飞行速度，其中X为速度。默认值为1（步行/跑步速度）</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.Flight.MaxSpeed.Bypass</td>
        <td>禁用飞行速度限制（仍适用全局限制）</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.Flight.MaxVSpeed.X</td>
        <td>设置最大垂直飞行速度。默认值为1</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.Flight.MaxVSpeed.Bypass</td>
        <td>禁用垂直飞行速度限制（仍适用全局限制）</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool</td>
        <td>提供对/PointTool的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.all</td>
        <td>授予所有指向工具权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.Destroy</td>
        <td>提供对Destroy工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdmin

Tools.PointTool.Jump</td>
        <td>提供对Jump工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.Utility</td>
        <td>提供对Utility工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.Kill</td>
        <td>提供对Kill工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.CheckOwner</td>
        <td>提供对CheckOwner工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.Repair</td>
        <td>提供对Repair工具的访问权限</td>
    </tr>
    <tr>
        <td>ShimmysAdminTools.PointTool.DestroyOtherPlayersStuff</td>
        <td>授予摧毁其他玩家车辆/建筑物的权限</td>
    </tr>
</table>
其余的权限通过各自的命令授予。

## Screenshots

### Command Spy
Command spy displays the commands of other players and admins. It's a useful tool to keep an eye on commands without needing console.
An example of command spy in action:

<img src="https://cdn.discordapp.com/attachments/658867220314587162/735449754862878770/unknown.png" width="500px">

# Downloads
You can download this plugin from the <a href="https://github.com/ShimmyMySherbet/ShimmysAdminTools/releases/">Releases</a> page.

# Donate
I maintain and develop this product for free and for everyone to use. If your feeling generous and want to support my open source work, you can donate/sponsor the project on my Ko-Fi <a href="https://ko-fi.com/shimmymysherbet">Here</a>. Even $3 goes a long way.
