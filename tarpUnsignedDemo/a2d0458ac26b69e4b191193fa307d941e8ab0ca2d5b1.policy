@id("allow_supreme_ruler")
permit(
  principal is Jans::User,
  action,
  resource
)
when {
  principal has role &&
  principal.role.contains("SupremeRuler")
};