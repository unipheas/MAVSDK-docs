# dronecode_sdk Namespace Reference

----

Namespace for all [dronecode_sdk](namespacedronecode__sdk.md) types.


## Data Structures

* [dronecode_sdk::Action](classdronecode__sdk_1_1_action.md)
* [dronecode_sdk::Calibration](classdronecode__sdk_1_1_calibration.md)
* [dronecode_sdk::Camera](classdronecode__sdk_1_1_camera.md)
* [dronecode_sdk::DronecodeSDK](classdronecode__sdk_1_1_dronecode_s_d_k.md)
* [dronecode_sdk::FollowMe](classdronecode__sdk_1_1_follow_me.md)
* [dronecode_sdk::Gimbal](classdronecode__sdk_1_1_gimbal.md)
* [dronecode_sdk::Info](classdronecode__sdk_1_1_info.md)
* [dronecode_sdk::LogFiles](classdronecode__sdk_1_1_log_files.md)
* [dronecode_sdk::MavlinkPassthrough](classdronecode__sdk_1_1_mavlink_passthrough.md)
* [dronecode_sdk::Mission](classdronecode__sdk_1_1_mission.md)
* [dronecode_sdk::MissionItem](classdronecode__sdk_1_1_mission_item.md)
* [dronecode_sdk::MissionRaw](classdronecode__sdk_1_1_mission_raw.md)
* [dronecode_sdk::Offboard](classdronecode__sdk_1_1_offboard.md)
* [dronecode_sdk::Param](classdronecode__sdk_1_1_param.md)
* [dronecode_sdk::PluginBase](classdronecode__sdk_1_1_plugin_base.md)
* [dronecode_sdk::System](classdronecode__sdk_1_1_system.md)
* [dronecode_sdk::Telemetry](classdronecode__sdk_1_1_telemetry.md)

## Enumerations

Type | Description
--- | ---
enum [ConnectionResult](#namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96) | Result type returned when adding a connection.
enum [ComponentType](#namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823e) | Component Types.

## Functions

Type | Name | Description
--- | --- | ---
const char * | [connection_result_str](#namespacedronecode__sdk_1a4f99d135d291363375982e84b6928f38) (const [ConnectionResult](namespacedronecode__sdk.md#namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96) result) | Returns a human-readable English string for a ConnectionResult.
bool | [operator==](#namespacedronecode__sdk_1a82242e25d08fb2850466f638701c7540) (const [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) & lhs, const [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) & rhs) | Equal operator to compare two [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1aa7c99052d48e71a3ac48569651485d42) (std::ostream & str, [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) const & video_stream_settings) | Stream operator to print information about a [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md).
bool | [operator==](#namespacedronecode__sdk_1a02742286ab6aaaa6df3de594bc20b749) (const [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) & lhs, const [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) & rhs) | Equal operator to compare two [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1ad8a864387c1cfecba3a1f03e5a282930) (std::ostream & str, [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) const & video_stream_info) | Stream operator to print information about a [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1a97e8676daa01b814bca7f65dc9e9ac7e) (std::ostream & str, [Camera::VideoStreamInfo::Status](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md#structdronecode__sdk_1_1_camera_1_1_video_stream_info_1a69b67b304c04a7d9bb0a8efb43927c85) const & video_stream_info_status) | Stream operator to print information about a [Camera::VideoStreamInfo::Status](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md#structdronecode__sdk_1_1_camera_1_1_video_stream_info_1a69b67b304c04a7d9bb0a8efb43927c85).
bool | [operator==](#namespacedronecode__sdk_1a07cc6e440564c2d7df62cad87257cd76) (const [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) & lhs, const [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) & rhs) | Equal operator to compare two [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a7830ff2413c4a1846365f69e37212c53) (std::ostream & str, [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) const & capture_info) | Stream operator to print information about a [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md).
bool | [operator==](#namespacedronecode__sdk_1a0f55e3a611b189a4226f781d6e1e6a79) (const [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) & lhs, const [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) & rhs) | Equal operator to compare two [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1ab42bdc52694ac9b0536d2f54498f2a3f) (std::ostream & str, [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) const & position) | Stream operator to print information about a [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md).
bool | [operator==](#namespacedronecode__sdk_1a7d2a4365c11cbdb95b75461b3e89fadb) (const [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) & lhs, const [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) & rhs) | Equal operator to compare two [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a70ac9b5c74bd9a096310437d15b7a7af) (std::ostream & str, [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) const & quaternion) | Stream operator to print information about a [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md).
bool | [operator==](#namespacedronecode__sdk_1a76036f0cedd4f8e1563a7bbb3c466fde) (const [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) & lhs, const [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) & rhs) | Equal operator to compare two [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a1e7dda26b31744e5dfc7f3bdd04bdfec) (std::ostream & str, [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) const & euler_angle) | Stream operator to print information about a [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md).
bool | [operator==](#namespacedronecode__sdk_1aff9ef154aeb90ee7d4c45b5105e2ca64) (const [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) & lhs, const [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) & rhs) | Equal operator to compare two [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a07d9af9a6403f725836286d9c310d16a) (std::ostream & str, [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) const & status) | Stream operator to print information about a [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1a3da4cb141f25449077e53da307d99d0b) (std::ostream & str, [Camera::Status::StorageStatus](structdronecode__sdk_1_1_camera_1_1_status.md#structdronecode__sdk_1_1_camera_1_1_status_1ad5fe84902ac4bba14fa77825f1828879) const & storage_status) | Stream operator to print information about a [Camera::Status::StorageStatus](structdronecode__sdk_1_1_camera_1_1_status.md#structdronecode__sdk_1_1_camera_1_1_status_1ad5fe84902ac4bba14fa77825f1828879).
bool | [operator==](#namespacedronecode__sdk_1a596966db6df9040ecf28a89d68dacbe1) (const [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) & lhs, const [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) & rhs) | Equal operator to compare two [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a0b5d611637e34d8e86ed27089a3b3e8f) (std::ostream & str, [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) const & setting) | Stream operator to print information about a [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md).
bool | [operator==](#namespacedronecode__sdk_1a20a75b99effdc66a173a8c004cee5d2c) (const [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) & lhs, const [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) & rhs) | Equal operator to compare two [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a06b19acda75aa4e8a94da496f98ba365) (std::ostream & str, [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) const & option) | Stream operator to print information about a [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md).
bool | [operator==](#namespacedronecode__sdk_1a331f8f2bf99003deb769b3b1475a33ef) (const [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) & lhs, const [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) & rhs) | Equal operator to compare two [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a12ce002e343392b13fd8aee1dd58a1a7) (std::ostream & str, [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) const & setting_options) | Stream operator to print information about a [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md).
bool | [operator==](#namespacedronecode__sdk_1add402a7e54e431c79040066cf0eb009a) (const [MissionItem](classdronecode__sdk_1_1_mission_item.md) & lhs, const [MissionItem](classdronecode__sdk_1_1_mission_item.md) & rhs) | Equal operator to compare two [MissionItem](classdronecode__sdk_1_1_mission_item.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a099ffe3cf3144ce815d31b2d1798ee1f) (std::ostream & str, [MissionItem](classdronecode__sdk_1_1_mission_item.md) const & mission_item) | Stream operator to print infos about a [MissionItem](classdronecode__sdk_1_1_mission_item.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1aba2a59ff24c643d38cd2f8f953d12aa0) (std::ostream & str, [MissionItem::CameraAction](classdronecode__sdk_1_1_mission_item.md#classdronecode__sdk_1_1_mission_item_1a636a841437572871ab82e01e1c41f447) const & camera_action) | Stream operator to print infos about a [MissionItem::CameraAction](classdronecode__sdk_1_1_mission_item.md#classdronecode__sdk_1_1_mission_item_1a636a841437572871ab82e01e1c41f447).
bool | [operator==](#namespacedronecode__sdk_1a681c639d97b9212243038edd9e255177) (const [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) & lhs, const [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) & rhs) | Equal operator to compare two [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a76198dd0c20cef978ef3a06832325a55) (std::ostream & str, [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) const & attitude_rate) | Stream operator to print information about a [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md).
bool | [operator==](#namespacedronecode__sdk_1a2b45a0749fc1fc43edec1885021929d4) (const [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) & lhs, const [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) & rhs) | Equal operator to compare two [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a068c09d23cddb5afc265efae6f1dacd1) (std::ostream & str, [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) const & position_ned_yaw) | Stream operator to print information about a [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md).
bool | [operator==](#namespacedronecode__sdk_1a72f45c81c82b40facfbbe8e285104005) (const [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) & lhs, const [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) & rhs) | Equal operator to compare two [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1abfc5394df8c9b9065db92e9d0f7a5293) (std::ostream & str, [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) const & velocity_body_yawspeed) | Stream operator to print information about a [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md).
bool | [operator==](#namespacedronecode__sdk_1ae5d6f7a8f8a7454983371f9444ed3c4b) (const [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) & lhs, const [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) & rhs) | Equal operator to compare two [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a116282786dfc4ef5492382f5a3d0b08a) (std::ostream & str, [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) const & velocity_ned_yaw) | Stream operator to print information about a [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md).
bool | [operator==](#namespacedronecode__sdk_1a70e13ff33048ec0b6a8d100dc813a84a) (const [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) & lhs, const [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) & rhs) | Equal operator to compare two [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) objects.
bool | [operator==](#namespacedronecode__sdk_1aeee7bba4738b277d079f347b8f48a1e7) (const [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) & lhs, const [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) & rhs) | Equal operator to compare two [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a1d3838c8844e1dc4a784c789f29f5267) (std::ostream & str, [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) const & position) | Stream operator to print information about a [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1a1fa26d63643cccf9c7b8a2361ba20688) (std::ostream & str, [Telemetry::PositionNED](structdronecode__sdk_1_1_telemetry_1_1_position_n_e_d.md) const & position_ned) | Stream operator to print information about a [Telemetry::PositionNED](structdronecode__sdk_1_1_telemetry_1_1_position_n_e_d.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1ad94e3e98805a83094010f1ed0599005f) (std::ostream & str, [Telemetry::VelocityNED](structdronecode__sdk_1_1_telemetry_1_1_velocity_n_e_d.md) const & velocity_ned) | Stream operator to print information about a [Telemetry::VelocityNED](structdronecode__sdk_1_1_telemetry_1_1_velocity_n_e_d.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1a52df542023f743fd2ad0dd647389a0ab) (std::ostream & str, [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) const & position_velocity_ned) | Stream operator to print information about a [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md).
bool | [operator==](#namespacedronecode__sdk_1a023eddb27d7cee0950801ce1e1445ada) (const [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) & lhs, const [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) & rhs) | Equal operator to compare two [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a28f6d4519e116bed2fb0457455742ee1) (std::ostream & str, [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) const & health) | Stream operator to print information about a [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md).
bool | [operator==](#namespacedronecode__sdk_1ab03745281710b020b9ac76daf16140ed) (const [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) & lhs, const [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) & rhs) | Equal operator to compare two [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1ae92c2a91b6fa86a56494a6086299d60d) (std::ostream & str, [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) const & gps_info) | Stream operator to print information about a [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md).
bool | [operator==](#namespacedronecode__sdk_1a5cb7b16c1ebe37da78b81a40da3137da) (const [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) & lhs, const [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) & rhs) | Equal operator to compare two [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a6299693fefce3144cf2ba0a27c4dd955) (std::ostream & str, [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) const & battery) | Stream operator to print information about a [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md).
bool | [operator==](#namespacedronecode__sdk_1aa65226e58f9b3c7f134d9c195ece6424) (const [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) & lhs, const [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) & rhs) | Equal operator to compare two [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a082304afec256131fcc09564cbc805e5) (std::ostream & str, [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) const & quaternion) | Stream operator to print information about a [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md).
bool | [operator==](#namespacedronecode__sdk_1aa6e3534d0274ff548533fe554938c46c) (const [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) & lhs, const [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) & rhs) | Equal operator to compare two [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a5ffcb10a86abe49a909a3641689974de) (std::ostream & str, [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) const & euler_angle) | Stream operator to print information about a [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md).
bool | [operator==](#namespacedronecode__sdk_1aaf687fbbe3cfe22bc3f5af30595d4b2e) (const [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) & lhs, const [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) & rhs) | Equal operator to compare two [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1ab1411c69c211b5eb231f1ad4ff893679) (std::ostream & str, [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) const & ground_speed) | Stream operator to print information about a [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md).
bool | [operator==](#namespacedronecode__sdk_1a2146a33adf4b5d158aff9b6e53fd06ab) (const [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) & lhs, const [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) & rhs) | Equal operator to compare two [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) objects.
std::ostream & | [operator<<](#namespacedronecode__sdk_1a4acb99b3d173ad128a4083096dac1995) (std::ostream & str, [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) const & rc_status) | Stream operator to print information about a [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md).
std::ostream & | [operator<<](#namespacedronecode__sdk_1ac4d265b14ca92c347875ef8f85a2d2eb) (std::ostream & str, [Telemetry::StatusText](structdronecode__sdk_1_1_telemetry_1_1_status_text.md) const & status_text) | Stream operator to print information about a [Telemetry::StatusText](structdronecode__sdk_1_1_telemetry_1_1_status_text.md).

## Enumeration Type Documentation


### enum ConnectionResult {#namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96}

```
#include: connection_result.h
```


Result type returned when adding a connection.

**Note**: [DronecodeSDK](classdronecode__sdk_1_1_dronecode_s_d_k.md) does not throw exceptions. Instead a result of this type will be returned when you add a connection: add_udp_connection().

Value | Description
--- | ---
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96ad0749aaba8b833466dfcbb0428e4f89c"></span> `SUCCESS` | Connection succeeded. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a070a0fb40f6c308ab544b227660aadff"></span> `TIMEOUT` | Connection timed out. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96aac87548d79aa92c60dcfac06ae83e5ad"></span> `SOCKET_ERROR` | Socket error. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96af69a41125696a14c45a8182ce7ba83a7"></span> `BIND_ERROR` | Bind error. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a20766ec998922f65e7ac718b7a9b7a22"></span> `SOCKET_CONNECTION_ERROR` | Socket connection error. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96ac77f1f09dab2c0c9980fca7cfae02518"></span> `CONNECTION_ERROR` | Connection error. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a3e860a081575fc82cc7b6ed2ca602947"></span> `NOT_IMPLEMENTED` | Connection type not implemented. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a222a5d8795464ca9a47b49daf1357538"></span> `SYSTEM_NOT_CONNECTED` | No system is connected. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a5a426189f0eb9043da73058f959c2ba1"></span> `SYSTEM_BUSY` | System is busy. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a6fa4dbf368cea972db8d9156799d5dbe"></span> `COMMAND_DENIED` | Command is denied. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a588cf56f08269878b055227a8490de67"></span> `DESTINATION_IP_UNKNOWN` | Connection IP is unknown. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a9532aa7fe8e205a02479a2e43d05f6b1"></span> `CONNECTIONS_EXHAUSTED` | Connections exhausted. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a269972fd1df83e8f423abead920f8780"></span> `CONNECTION_URL_INVALID` | URL invalid. 
<span id="namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96a70b509145d288ea71f707a45fa6538bb"></span> `BAUDRATE_UNKNOWN` | Baudrate unknown. 

### enum ComponentType {#namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823e}

```
#include: system.h
```


Component Types.


Value | Description
--- | ---
<span id="namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823eaf3017582814e5f96b7281b7b561ba685"></span> `UNKNOWN` |  
<span id="namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823ea465bc7e344d319648550ecbf186533cf"></span> `AUTOPILOT` |  
<span id="namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823eafd8eef12b6ff726e56d809b955def4e0"></span> `CAMERA` |  
<span id="namespacedronecode__sdk_1a19aedbe22879fce9e10f588c16ee823ea91ec9534b0a4ee9ba9daf730dd057aec"></span> `GIMBAL` |  

## Function Documentation


### connection_result_str() {#namespacedronecode__sdk_1a4f99d135d291363375982e84b6928f38}

```
#include: connection_result.h
```
```cpp
const char* dronecode_sdk::connection_result_str(const ConnectionResult result)
```


Returns a human-readable English string for a ConnectionResult.


**Parameters**

* const [ConnectionResult](namespacedronecode__sdk.md#namespacedronecode__sdk_1a8ba260cb5fc0837533a86e236d205c96) **result** - The enum value for which a human readable string is required.

**Returns**

&emsp;const char * - Human readable string for the ConnectionResult.

### operator==() {#namespacedronecode__sdk_1a82242e25d08fb2850466f638701c7540}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::VideoStreamSettings &lhs, const Camera::VideoStreamSettings &rhs)
```


Equal operator to compare two [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) objects.


**Parameters**

* const [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md)& **lhs** - 
* const [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1aa7c99052d48e71a3ac48569651485d42}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::VideoStreamSettings const &video_stream_settings)
```


Stream operator to print information about a [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::VideoStreamSettings](structdronecode__sdk_1_1_camera_1_1_video_stream_settings.md) const& **video_stream_settings** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a02742286ab6aaaa6df3de594bc20b749}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::VideoStreamInfo &lhs, const Camera::VideoStreamInfo &rhs)
```


Equal operator to compare two [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) objects.


**Parameters**

* const [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md)& **lhs** - 
* const [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1ad8a864387c1cfecba3a1f03e5a282930}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::VideoStreamInfo const &video_stream_info)
```


Stream operator to print information about a [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::VideoStreamInfo](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md) const& **video_stream_info** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1a97e8676daa01b814bca7f65dc9e9ac7e}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::VideoStreamInfo::Status const &video_stream_info_status)
```


Stream operator to print information about a [Camera::VideoStreamInfo::Status](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md#structdronecode__sdk_1_1_camera_1_1_video_stream_info_1a69b67b304c04a7d9bb0a8efb43927c85).


**Parameters**

* std::ostream& **str** - 
* [Camera::VideoStreamInfo::Status](structdronecode__sdk_1_1_camera_1_1_video_stream_info.md#structdronecode__sdk_1_1_camera_1_1_video_stream_info_1a69b67b304c04a7d9bb0a8efb43927c85) const& **video_stream_info_status** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a07cc6e440564c2d7df62cad87257cd76}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::CaptureInfo &lhs, const Camera::CaptureInfo &rhs)
```


Equal operator to compare two [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) objects.


**Parameters**

* const [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md)& **lhs** - 
* const [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a7830ff2413c4a1846365f69e37212c53}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::CaptureInfo const &capture_info)
```


Stream operator to print information about a [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::CaptureInfo](structdronecode__sdk_1_1_camera_1_1_capture_info.md) const& **capture_info** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a0f55e3a611b189a4226f781d6e1e6a79}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::CaptureInfo::Position &lhs, const Camera::CaptureInfo::Position &rhs)
```


Equal operator to compare two [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) objects.


**Parameters**

* const [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md)& **lhs** - 
* const [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1ab42bdc52694ac9b0536d2f54498f2a3f}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::CaptureInfo::Position const &position)
```


Stream operator to print information about a [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) const& **position** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a7d2a4365c11cbdb95b75461b3e89fadb}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::CaptureInfo::Quaternion &lhs, const Camera::CaptureInfo::Quaternion &rhs)
```


Equal operator to compare two [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) objects.


**Parameters**

* const [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md)& **lhs** - 
* const [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a70ac9b5c74bd9a096310437d15b7a7af}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::CaptureInfo::Quaternion const &quaternion)
```


Stream operator to print information about a [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) const& **quaternion** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a76036f0cedd4f8e1563a7bbb3c466fde}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::CaptureInfo::EulerAngle &lhs, const Camera::CaptureInfo::EulerAngle &rhs)
```


Equal operator to compare two [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) objects.


**Parameters**

* const [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md)& **lhs** - 
* const [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a1e7dda26b31744e5dfc7f3bdd04bdfec}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::CaptureInfo::EulerAngle const &euler_angle)
```


Stream operator to print information about a [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) const& **euler_angle** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1aff9ef154aeb90ee7d4c45b5105e2ca64}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::Status &lhs, const Camera::Status &rhs)
```


Equal operator to compare two [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) objects.


**Parameters**

* const [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md)& **lhs** - 
* const [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a07d9af9a6403f725836286d9c310d16a}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::Status const &status)
```


Stream operator to print information about a [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::Status](structdronecode__sdk_1_1_camera_1_1_status.md) const& **status** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1a3da4cb141f25449077e53da307d99d0b}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::Status::StorageStatus const &storage_status)
```


Stream operator to print information about a [Camera::Status::StorageStatus](structdronecode__sdk_1_1_camera_1_1_status.md#structdronecode__sdk_1_1_camera_1_1_status_1ad5fe84902ac4bba14fa77825f1828879).


**Parameters**

* std::ostream& **str** - 
* [Camera::Status::StorageStatus](structdronecode__sdk_1_1_camera_1_1_status.md#structdronecode__sdk_1_1_camera_1_1_status_1ad5fe84902ac4bba14fa77825f1828879) const& **storage_status** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a596966db6df9040ecf28a89d68dacbe1}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::Setting &lhs, const Camera::Setting &rhs)
```


Equal operator to compare two [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) objects.


**Parameters**

* const [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md)& **lhs** - 
* const [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a0b5d611637e34d8e86ed27089a3b3e8f}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::Setting const &setting)
```


Stream operator to print information about a [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::Setting](structdronecode__sdk_1_1_camera_1_1_setting.md) const& **setting** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a20a75b99effdc66a173a8c004cee5d2c}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::Option &lhs, const Camera::Option &rhs)
```


Equal operator to compare two [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) objects.


**Parameters**

* const [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md)& **lhs** - 
* const [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a06b19acda75aa4e8a94da496f98ba365}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::Option const &option)
```


Stream operator to print information about a [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md) const& **option** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a331f8f2bf99003deb769b3b1475a33ef}

```
#include: plugins/camera/camera.h
```
```cpp
bool dronecode_sdk::operator==(const Camera::SettingOptions &lhs, const Camera::SettingOptions &rhs)
```


Equal operator to compare two [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) objects.


**Parameters**

* const [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md)& **lhs** - 
* const [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a12ce002e343392b13fd8aee1dd58a1a7}

```
#include: plugins/camera/camera.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Camera::SettingOptions const &setting_options)
```


Stream operator to print information about a [Camera::Option](structdronecode__sdk_1_1_camera_1_1_option.md).


**Parameters**

* std::ostream& **str** - 
* [Camera::SettingOptions](structdronecode__sdk_1_1_camera_1_1_setting_options.md) const& **setting_options** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1add402a7e54e431c79040066cf0eb009a}

```
#include: plugins/mission/mission_item.h
```
```cpp
bool dronecode_sdk::operator==(const MissionItem &lhs, const MissionItem &rhs)
```


Equal operator to compare two [MissionItem](classdronecode__sdk_1_1_mission_item.md) objects.


**Parameters**

* const [MissionItem](classdronecode__sdk_1_1_mission_item.md)& **lhs** - 
* const [MissionItem](classdronecode__sdk_1_1_mission_item.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a099ffe3cf3144ce815d31b2d1798ee1f}

```
#include: plugins/mission/mission_item.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, MissionItem const &mission_item)
```


Stream operator to print infos about a [MissionItem](classdronecode__sdk_1_1_mission_item.md).


**Parameters**

* std::ostream& **str** - 
* [MissionItem](classdronecode__sdk_1_1_mission_item.md) const& **mission_item** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1aba2a59ff24c643d38cd2f8f953d12aa0}

```
#include: plugins/mission/mission_item.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, MissionItem::CameraAction const &camera_action)
```


Stream operator to print infos about a [MissionItem::CameraAction](classdronecode__sdk_1_1_mission_item.md#classdronecode__sdk_1_1_mission_item_1a636a841437572871ab82e01e1c41f447).


**Parameters**

* std::ostream& **str** - 
* [MissionItem::CameraAction](classdronecode__sdk_1_1_mission_item.md#classdronecode__sdk_1_1_mission_item_1a636a841437572871ab82e01e1c41f447) const& **camera_action** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a681c639d97b9212243038edd9e255177}

```
#include: plugins/offboard/offboard.h
```
```cpp
bool dronecode_sdk::operator==(const Offboard::AttitudeRate &lhs, const Offboard::AttitudeRate &rhs)
```


Equal operator to compare two [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) objects.


**Parameters**

* const [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md)& **lhs** - 
* const [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a76198dd0c20cef978ef3a06832325a55}

```
#include: plugins/offboard/offboard.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Offboard::AttitudeRate const &attitude_rate)
```


Stream operator to print information about a [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md).


**Parameters**

* std::ostream& **str** - 
* [Offboard::AttitudeRate](structdronecode__sdk_1_1_offboard_1_1_attitude_rate.md) const& **attitude_rate** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a2b45a0749fc1fc43edec1885021929d4}

```
#include: plugins/offboard/offboard.h
```
```cpp
bool dronecode_sdk::operator==(const Offboard::PositionNEDYaw &lhs, const Offboard::PositionNEDYaw &rhs)
```


Equal operator to compare two [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) objects.


**Parameters**

* const [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md)& **lhs** - 
* const [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a068c09d23cddb5afc265efae6f1dacd1}

```
#include: plugins/offboard/offboard.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Offboard::PositionNEDYaw const &position_ned_yaw)
```


Stream operator to print information about a [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md).


**Parameters**

* std::ostream& **str** - 
* [Offboard::PositionNEDYaw](structdronecode__sdk_1_1_offboard_1_1_position_n_e_d_yaw.md) const& **position_ned_yaw** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a72f45c81c82b40facfbbe8e285104005}

```
#include: plugins/offboard/offboard.h
```
```cpp
bool dronecode_sdk::operator==(const Offboard::VelocityBodyYawspeed &lhs, const Offboard::VelocityBodyYawspeed &rhs)
```


Equal operator to compare two [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) objects.


**Parameters**

* const [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md)& **lhs** - 
* const [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1abfc5394df8c9b9065db92e9d0f7a5293}

```
#include: plugins/offboard/offboard.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Offboard::VelocityBodyYawspeed const &velocity_body_yawspeed)
```


Stream operator to print information about a [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md).


**Parameters**

* std::ostream& **str** - 
* [Offboard::VelocityBodyYawspeed](structdronecode__sdk_1_1_offboard_1_1_velocity_body_yawspeed.md) const& **velocity_body_yawspeed** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1ae5d6f7a8f8a7454983371f9444ed3c4b}

```
#include: plugins/offboard/offboard.h
```
```cpp
bool dronecode_sdk::operator==(const Offboard::VelocityNEDYaw &lhs, const Offboard::VelocityNEDYaw &rhs)
```


Equal operator to compare two [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) objects.


**Parameters**

* const [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md)& **lhs** - 
* const [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a116282786dfc4ef5492382f5a3d0b08a}

```
#include: plugins/offboard/offboard.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Offboard::VelocityNEDYaw const &velocity_ned_yaw)
```


Stream operator to print information about a [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md).


**Parameters**

* std::ostream& **str** - 
* [Offboard::VelocityNEDYaw](structdronecode__sdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md) const& **velocity_ned_yaw** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a70e13ff33048ec0b6a8d100dc813a84a}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::PositionVelocityNED &lhs, const Telemetry::PositionVelocityNED &rhs)
```


Equal operator to compare two [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) objects.


**Parameters**

* const [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md)& **lhs** - 
* const [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator==() {#namespacedronecode__sdk_1aeee7bba4738b277d079f347b8f48a1e7}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::Position &lhs, const Telemetry::Position &rhs)
```


Equal operator to compare two [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) objects.


**Parameters**

* const [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md)& **lhs** - 
* const [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a1d3838c8844e1dc4a784c789f29f5267}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::Position const &position)
```


Stream operator to print information about a [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::Position](structdronecode__sdk_1_1_telemetry_1_1_position.md) const& **position** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1a1fa26d63643cccf9c7b8a2361ba20688}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::PositionNED const &position_ned)
```


Stream operator to print information about a [Telemetry::PositionNED](structdronecode__sdk_1_1_telemetry_1_1_position_n_e_d.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::PositionNED](structdronecode__sdk_1_1_telemetry_1_1_position_n_e_d.md) const& **position_ned** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1ad94e3e98805a83094010f1ed0599005f}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::VelocityNED const &velocity_ned)
```


Stream operator to print information about a [Telemetry::VelocityNED](structdronecode__sdk_1_1_telemetry_1_1_velocity_n_e_d.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::VelocityNED](structdronecode__sdk_1_1_telemetry_1_1_velocity_n_e_d.md) const& **velocity_ned** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1a52df542023f743fd2ad0dd647389a0ab}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::PositionVelocityNED const &position_velocity_ned)
```


Stream operator to print information about a [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::PositionVelocityNED](structdronecode__sdk_1_1_telemetry_1_1_position_velocity_n_e_d.md) const& **position_velocity_ned** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a023eddb27d7cee0950801ce1e1445ada}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::Health &lhs, const Telemetry::Health &rhs)
```


Equal operator to compare two [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) objects.


**Parameters**

* const [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md)& **lhs** - 
* const [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a28f6d4519e116bed2fb0457455742ee1}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::Health const &health)
```


Stream operator to print information about a [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::Health](structdronecode__sdk_1_1_telemetry_1_1_health.md) const& **health** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1ab03745281710b020b9ac76daf16140ed}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::GPSInfo &lhs, const Telemetry::GPSInfo &rhs)
```


Equal operator to compare two [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) objects.


**Parameters**

* const [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md)& **lhs** - 
* const [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1ae92c2a91b6fa86a56494a6086299d60d}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::GPSInfo const &gps_info)
```


Stream operator to print information about a [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::GPSInfo](structdronecode__sdk_1_1_telemetry_1_1_g_p_s_info.md) const& **gps_info** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a5cb7b16c1ebe37da78b81a40da3137da}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::Battery &lhs, const Telemetry::Battery &rhs)
```


Equal operator to compare two [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) objects.


**Parameters**

* const [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md)& **lhs** - 
* const [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a6299693fefce3144cf2ba0a27c4dd955}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::Battery const &battery)
```


Stream operator to print information about a [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::Battery](structdronecode__sdk_1_1_telemetry_1_1_battery.md) const& **battery** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1aa65226e58f9b3c7f134d9c195ece6424}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::Quaternion &lhs, const Telemetry::Quaternion &rhs)
```


Equal operator to compare two [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) objects.


**Parameters**

* const [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md)& **lhs** - 
* const [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a082304afec256131fcc09564cbc805e5}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::Quaternion const &quaternion)
```


Stream operator to print information about a [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::Quaternion](structdronecode__sdk_1_1_telemetry_1_1_quaternion.md) const& **quaternion** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1aa6e3534d0274ff548533fe554938c46c}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::EulerAngle &lhs, const Telemetry::EulerAngle &rhs)
```


Equal operator to compare two [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) objects.


**Parameters**

* const [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md)& **lhs** - 
* const [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a5ffcb10a86abe49a909a3641689974de}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::EulerAngle const &euler_angle)
```


Stream operator to print information about a [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::EulerAngle](structdronecode__sdk_1_1_telemetry_1_1_euler_angle.md) const& **euler_angle** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1aaf687fbbe3cfe22bc3f5af30595d4b2e}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::GroundSpeedNED &lhs, const Telemetry::GroundSpeedNED &rhs)
```


Equal operator to compare two [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) objects.


**Parameters**

* const [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md)& **lhs** - 
* const [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1ab1411c69c211b5eb231f1ad4ff893679}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::GroundSpeedNED const &ground_speed)
```


Stream operator to print information about a [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::GroundSpeedNED](structdronecode__sdk_1_1_telemetry_1_1_ground_speed_n_e_d.md) const& **ground_speed** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator==() {#namespacedronecode__sdk_1a2146a33adf4b5d158aff9b6e53fd06ab}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
bool dronecode_sdk::operator==(const Telemetry::RCStatus &lhs, const Telemetry::RCStatus &rhs)
```


Equal operator to compare two [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) objects.


**Parameters**

* const [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md)& **lhs** - 
* const [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md)& **rhs** - 

**Returns**

&emsp;bool - `true` if items are equal.

### operator<<() {#namespacedronecode__sdk_1a4acb99b3d173ad128a4083096dac1995}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::RCStatus const &rc_status)
```


Stream operator to print information about a [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::RCStatus](structdronecode__sdk_1_1_telemetry_1_1_r_c_status.md) const& **rc_status** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.

### operator<<() {#namespacedronecode__sdk_1ac4d265b14ca92c347875ef8f85a2d2eb}

```
#include: plugins/telemetry/telemetry.h
```
```cpp
std::ostream& dronecode_sdk::operator<<(std::ostream &str, Telemetry::StatusText const &status_text)
```


Stream operator to print information about a [Telemetry::StatusText](structdronecode__sdk_1_1_telemetry_1_1_status_text.md).


**Parameters**

* std::ostream& **str** - 
* [Telemetry::StatusText](structdronecode__sdk_1_1_telemetry_1_1_status_text.md) const& **status_text** - 

**Returns**

&emsp;std::ostream & - A reference to the stream.